## <function> SMap </function> 
** Description **  :   
SMap projection of the input data file or DataFrame.

** Python **  :   
```python
SMap(pathIn='./', dataFile='', dataFrame=None, pathOut='./',
predictFile='', lib='', pred='', E=0, Tp=1, knn=0, tau=-1,
theta=0, exclusionRadius=0, columns='', target='',
smapCoefFile='', smapSVFile='', solver=None, embedded=False,
verbose=False, const_pred=False, showPlot=False,
validLib=[], ignoreNan=True, generateSteps=0,
generateLibrary=False, parameterList=False, noTime=False)
```

** R **  :   
```R
SMap(pathIn="./", dataFile="", dataFrame=NULL,
lib="", pred="", E=0, Tp=1, knn=0, tau=-1,
theta=0, exclusionRadius=0, columns="", target="", 
embedded=FALSE, verbose=FALSE, validLib=vector(), 
ignoreNan=TRUE, generateSteps=0, parameterList=FALSE, 
showPlot=FALSE, noTime=FALSE) 
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame | None |Input DataFrame|
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| theta     | int    | 0     | SMap localization | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name or index |
| smapCoefFile | string | ""    | SMap coefficient output file |
| smapSVFile | string | ""    | SMap singular value output file |
| solver    | sklearn.linear_model | None | Linear system solver |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| verbose   | bool   | False | Echo messages |
| const\_pred| bool  | False | Include non projected forecast data |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| validLib  | bool [] | [] or None | Conditional embedding |
| ignoreNan | bool   | True | Adjust lib to exlcude NaN |
| generateSteps | int  | 0     | Number of recursive time step predictions | 
| generateLibrary | bool | False | Add generated data to library | 
| parameterList | bool | False | Include parameter dictionary in return    |
| noTime    | bool | False | Do not require first data column of time or index |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes ** :   
If `embedded` is false, data columns are embedded to dimension `E` with shift `tau`.</br/>
If `predictFile` is provided the predictions are written in csv format.<br/>
If `smapFile` is provided the coefficients are written in csv format.<br/>
If `knn` is not specified, it is set equal to the library size.<br/>
If `knn` is specified, it must be greater than `E`.<br/>
If `nan` are detected in `columns` or `target` the corresponding rows are removed prior to time-delay embedding. This may invalidate presumptions of Takens theorem.

`validLib` implements conditional embedding (CE). It is a boolean vector the same length as the number of time series rows. A `false` entry means that the state-space vector derived from the corresponding time series row will not be included in the state-space library. See [`examples`](./cond_emb_demo.ipynb).

If generateSteps > 0 `SMap` operates in feedback generative mode. The values of `pred` are over-riden to start at the end of the data. At each step one prediction is made, added to the `columns` data, a new time-delay embedded is created, and the cycle repeated for `generateSteps`. Feedback generation only operates on a univariate time series that is time-delay embedded. The `columns` and `target` variables must be the same.

** Embedding ** :   
`SMap` should be called with columns explicitly corresponding to
dimensions `E`. In the univariate case (number of `columns` = 1) with
default `embedded = false`, the time series will be time-delay
embedded to dimension `E`, returned `SMap` coefficients correspond to each dimension. 

If a multivariate data is used (number of `columns` > 1) `SMap`
must use `embedded = true` with `E` equal to the number of columns.
This prevents the function from internally time-delay embedding the
multiple columns to dimension `E`.  If internal time-delay embedding
were performed, then state-space columns will not correspond to the
intended dimensions in the matrix inversion, coefficient assignment,
and prediction.  In this multivariate case, the user can first prepare
the embedding (using [`Embed()`](../edm_functions/#embed) for time-delay
embedding if desired, add a first column of time), then pass this embedding 
to `SMap` with appropriately specified `columns`, `E`, and `embedded = true`.
The [`Embedding.py`](https://github.com/SugiharaLab/pyEDM/blob/master/pyEDM/etc/apps/Embedding.py) application can be used to perform the embedding and
insert the time vector for input to `SMap`.

** Linear System Solver ** :   
In `pyEDM`: The default LAPACK SVD solver `dgelss()` can be replaced with
a class object instantiated from the `sklearn.linear_model` class.
Supported solvers include `LinearRegression`, `Ridge`, `Lasso`,
`ElasticNet`, `RidgeCV`, `LassoCV`, `ElasticNetCV`. See [`examples`](./solvers_demo.ipynb).

** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with two DataFrames:<br/>
`predictions` [ 3 columns : "Time", "Observations", "Predictions"],<br/>
`coefficients`[ E+2 columns : "Time", and E+1 SMap coefficents]<br/>
If `parameterList = True`, a dictionary of `parameters` is added.

`nan` values are inserted in the output DataFrame where there is 
no observation or prediction.
