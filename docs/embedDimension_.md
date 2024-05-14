## <function> EmbedDimension </function> 
** Description **  :   
Evaluate Simplex prediction skill for embedding dimensions from 1 to `maxE`.

** Python **  :   
```python
EmbedDimension(dataFrame=None, columns='', target='',
maxE=10, lib='', pred='', Tp=1, tau=-1, exclusionRadius=0, 
embedded=False, validLib=[], noTime=False, ignoreNan=True,
verbose=False, numProcess=4, showPlot=True)
```

** R **  :   
```R
EmbedDimension(pathIn="./", dataFile="", dataFrame=NULL,
pathOut="", predictFile="", lib="", pred="",
maxE=10, Tp=1, tau=-1, exclusionRadius=0,
columns="", target="",  embedded=FALSE, verbose=FALSE,
validLib=vector(), numThreads=4, showPlot=TRUE, noTime=FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| maxE      | int    | 10    | Evaluate embedding up to maxE | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| validLib  | bool [] | [] or None | Conditional embedding |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |
| noTime    | bool | False | Do not require first data column of time or index |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
Version 1.x: `numThreads` defines the number of worker threads for the `maxE` embeddings.

Version 2.x: `numProcess` defines the number of processes for the `maxE` embeddings.

** Returns **  :   
DataFrame with columns `E` and `rho`.   
