
## <function> PredictNonlinear </function> 
** Description **  :   
Evaluate SMap prediction skill for localization parameter 
`theta`  (default from 0.01 to 9).

** Python **  :   
```python
PredictNonlinear(dataFrame=None, columns='', target='', 
theta='', lib='', pred='', E=1, Tp=1, knn=0, tau=-1,
exclusionRadius=0, solver=None, embedded=False, 
validLib=[], noTime=False, ignoreNan=True, 
verbose=False, numProcess=4, showPlot=True)
```

** R **  :   
```R
PredictNonlinear(pathIn="./", dataFile="", dataFrame=NULL, 
pathOut="./", predictFile="", lib="", pred="", theta="",
E=1, Tp=1, knn=0, tau=-1, exclusionRadius=0,
columns="", target="", embedded=FALSE, verbose=FALSE,
validLib=vector(), ignoreNan=TRUE, numThreads=4,
showPlot=TRUE, noTime=FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| theta     | string | ""    | `theta` is a string of theta values with a delimit| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
er of [',' , '\t', '\n']. |
| E         | int    | 0     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| solver    | sklearn.linear_model | None | Linear system solver |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| validLib  | bool [] | [] or None | Conditional embedding |
| noTime    | bool | False | Do not require first data column of time or index |
| ignoreNan | bool   | True | Adjust lib to exlcude NaN |
| verbose   | bool   | False | Echo messages |
| numThreads | int   | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of theta vs Rho |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
`theta` is a list or string of theta values with a delimiter of 
[',', '\t', '\n'].
See the Parameters table for parameter definitions.

Version 1.x: `numThreads` defines the number of worker threads for the `maxTp` embeddings.

Version 2.x: `numProcess` defines the number of processes for the `maxTp` embeddings.

** Returns **  :   
DataFrame with columns `theta` and `rho`. 
