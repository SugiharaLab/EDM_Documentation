
## <function> PredictNonlinear </function> 
** Description **  :   
Evaluate SMap prediction skill for localization parameter 
`theta`  (default from 0.01 to 9).

** Python **  :   
```python
PredictNonlinear(pathIn='./', dataFile='', dataFrame=None, 
pathOut='./', predictFile='', lib='', pred='', theta='', 
E=1, Tp=1, knn=0, tau=-1, exclusionRadius=0, columns='', 
target='', embedded=False, verbose=False, ignoreNan=True,
validLib=[], numThreads=4, showPlot=True, noTime=False)
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
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| theta     | string | ""    | `theta` is a string of theta values with a delimiter of [',' , '\t', '\n']. |
| E         | int    | 0     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| verbose   | bool   | False | Echo messages |
| validLib  | bool [] | [] or None | Conditional embedding |
| ignoreNan | bool   | True | Adjust lib to exlcude NaN |
| numThreads | int   | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of theta vs Rho |
| noTime    | bool | False | Do not require first data column of time or index |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
`theta` is a string of theta values with a delimiter of [',', '\t', '\n'].
See the Parameters table for parameter definitions.

** Returns **  :   
DataFrame with columns `theta` and `rho`. 
