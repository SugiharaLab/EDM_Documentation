
## <function> Multiview </function> 
** Description **  :   
Multiview embedding and forecasting of the input data file or DataFrame.

** Python **  :   
```python
Multiview(pathIn='./', dataFile='', dataFrame=None,
pathOut='./', predictFile='', lib='', pred='', D=0,
E=1, Tp=1, knn=0, tau=-1, columns='', target='',
multiview=0, exclusionRadius=0, trainLib=True,
excludeTarget=False, parameterList=False,
verbose=False, numThreads=4, showPlot=False, 
noTime = False)
```

** R **  :   
```R
Multiview(pathIn="./", dataFile="", dataFrame=NULL,
lib="", pred="", D=0, E=1, Tp=1, knn=0,
tau=-1, columns="", target="", multiview=0,
exclusionRadius=0, trainLib=TRUE, 
excludeTarget=FALSE, parameterList=FALSE,
verbose=FALSE,  numThreads=4, showPlot=FALSE, noTime=FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| D         | int    | N cols| Multiview state-space dimension | 
| E         | int    | 1     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set to E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target library column name |
| multiview | int    | 0     | Multiview parameter : (if 0 then set to 'sqrt(C)' where C is the number of  D-dimensional combinations out of all available data vectors)|
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| trainLib  | bool   | True  | Use in-sample (lib=pred) prediction for ranking |
| excludeTarget | bool | False | Exclude target variable from multiviews |
| parameterList | bool | False | Include parameter dictionary in return    |
| numThreads| int    | 4     | Number of threads to use |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| noTime    | bool | False | Do not require first data column of time or index |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
If `predictFile` is provided the Predictions will be written to it in csv format.

If `multiview` is not specified it is set to 'sqrt(C)' where C is the number of 
`D`-dimensional combinations out of all available data vectors.

** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with two DataFrames:<br/>
View<br/>
Predictions<br/>

The `Predictions` DataFrame has 3 columns: `Time`, `Observations`, `Predictions`.   
The `View` DataFrame has `E`+3 columns.   
The first `E` columns are the the column indices in the input data DataFrame 
that are embedded and applied to Simplex prediction.   
The last three columns are "rho", "MAE", "RMSE" corresponding to the prediction 
Pearson correlation, maximum absolute error and root mean square error.<br/>

If `parameterList = True`, a dictionary of `parameters` is added.

`nan` values are inserted where there is no observation or prediction.
