
## <function> PredictInterval </function> 
** Description **  :   
Evaluate Simplex prediction skill for forecast intervals from 1 to maxTp.

** Python **  :   
```python
PredictInterval(dataFrame=None, columns='', target='',
lib='', pred='', maxTp=10, E=1, tau=-1, exclusionRadius=0,
embedded=False, validLib=[], noTime=False, ignoreNan=True,
verbose=False, numProcess=4, showPlot=True)
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
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| maxTp     | int    | 10    | Evaluate forecast with Tp up to maxTp | 
| E         | int    | 0     | Embedding dimension | 
| tau       | int    | -1    | Embedding shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| embedded  | bool   | False | Is data an embedding?  |
| validLib  | bool [] | [] or None | Conditional embedding |
| noTime    | bool | False | Do not require first data column of time or index |
| verbose   | bool   | False | Echo messages |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
Version 1.x: `numThreads` defines the number of worker threads for the `maxTp` embeddings.

Version 2.x: `numProcess` defines the number of processes for the `maxTp` embeddings.

** Returns **  :   
DataFrame with columns `Tp` and `rho`. 
