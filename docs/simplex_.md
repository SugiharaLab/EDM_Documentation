## <function> Simplex </function> 
** Description **  :   
Simplex projection of the input data file or DataFrame.

** Python **  :   
```python
Simplex(dataFrame=None, columns='', target='', 
lib='', pred='', E=0, Tp=1, knn=0, tau=-1, 
exclusionRadius=0, embedded=False, validLib=[], 
noTime = False, verbose=False, showPlot=False, 
ignoreNan = True, returnObject=False)
```

** R **  :   
```R
Simplex(pathIn="./", dataFile="", dataFrame=NULL, 
pathOut="./", predictFile="", lib="", pred="", 
E=0, Tp=1, knn=0, tau=-1, exclusionRadius=0, 
columns="", target="", embedded=FALSE, 
const_pred=FALSE, verbose=FALSE, validLib=vector(), 
generateSteps=0, parameterList=FALSE, 
showPlot=FALSE, noTime=FALSE) 
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame | None |Input DataFrame|
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set to E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows)| 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| embedded  | bool   | False | Is data an embedding? If False, embed to E|
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| validLib  | bool [] | [] or None | Condtional embedding |
| noTime    | bool | False | Do not require first data column of time or index |
| returnObject | bool | False | pyEDM : return Simplex class object |
| generateSteps | int  | 0   | Number of recursive time step predictions | 
| generateLibrary | bool | False | Add generated data to library | 
| parameterList | bool | False | Include parameter dictionary in return |
| const\_pred| bool  | False | Include non projected forecast data |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes ** :   
If `embedded` is false (default) the data `columns` are embedded to dimension `E` with time shift `tau`.  If `knn` = 0, it is set to E+1.

Version 1.x : `nan` values are passed through all numeric computations in `cppEDM`. Any prediction row (`pred`) with `nan` will result in `nan` simplex prediction. Any library vector with a `nan` , whether in the observation, or from time delay embedding used as a nearest neighbor, will result in `nan` simplex prediction.

Version 2.x : `nan` values are removed from the data unless `ignoreNan = True`. 

`validLib` implements conditional embedding (CE). It is a boolean vector the same length as the number of time series rows. A `false` entry means that the state-space vector derived from the corresponding time series row will not be included in the state-space library. See [`examples`](./cond_emb_demo.ipynb).

If generateSteps > 0 `Simplex` operates in feedback generative mode. The values of `pred` are over-riden to start at the end of the data. At each step one prediction is made, added to the `columns` data, a new time-delay embedded is created, and the cycle repeated for `generateSteps`. Feedback generation only operates on a univariate time series that is time-delay embedded. The `columns` and `target` variables must be the same.

** Returns **  :   
Version 1.x : If `parameterList = False`, (default) returns a DataFrame with 3 columns : "Time", "Observations", "Predictions". If `parameterList = True`, returns a list with `predictions`, `parameters`.

Version 2.x : Returns a DataFrame with 3 columns : "Time", "Observations", "Predictions". If `returnObject = True` returns the Simplex class object with all data and variables. 
