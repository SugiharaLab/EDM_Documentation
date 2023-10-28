
## <function> PredictInterval </function> 
** Description **  :   
Evaluate Simplex prediction skill for forecast intervals from 1 to maxTp.

** Python **  :   
```python
PredictInterval(pathIn='./', dataFile='', dataFrame=None,
pathOut='./', predictFile='', lib='', pred='', maxTp=10,
E=1, tau=-1, exclusionRadius=0, columns='', target='',
embedded=False, verbose=False, validLib=[], numThreads=4,
showPlot=True, noTime=False)
```

** R **  :   
```R
PredictInterval(pathIn="./", dataFile="", dataFrame=NULL,
pathOut="./",  predictFile="", lib="", pred="",
maxTp=10, E=1,  tau=-1, exclusionRadius=0, columns="",
target="", embedded=FALSE, verbose=FALSE,
validLib=vector(), numThreads=4, showPlot=TRUE, noTime=FALSE)
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
| maxTp     | int    | 10    | Evaluate forecast with Tp up to maxTp | 
| E         | int    | 0     | Embedding dimension | 
| tau       | int    | -1    | Embedding shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding?  |
| verbose   | bool   | False | Echo messages |
| validLib  | bool [] | [] or None | Conditional embedding |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |
| noTime    | bool | False | Do not require first data column of time or index |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
`numThreads` defines the number of worker threads for the `maxTp` prediction 
interval forecasts.

** Returns **  :   
DataFrame with columns `Tp` and `rho`. 
