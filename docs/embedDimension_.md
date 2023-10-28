## <function> EmbedDimension </function> 
** Description **  :   
Evaluate Simplex prediction skill for embedding dimensions from 1 to `maxE`.

** Python **  :   
```python
EmbedDimension(pathIn='./', dataFile='', dataFrame=None,
pathOut='./', predictFile='', lib='', pred='', maxE=10,
Tp=1, tau=-1, exclusionRadius=0, columns='', target='',
embedded=False, verbose=False, validLib=[], numThreads=4,
showPlot=True, noTime=False)
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
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| maxE      | int    | 10    | Evaluate embedding up to maxE | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| validLib  | bool [] | [] or None | Conditional embedding |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |
| noTime    | bool | False | Do not require first data column of time or index |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
`numThreads` defines the number of worker threads for the `maxE` embeddings.

** Returns **  :   
DataFrame with columns `E` and `rho`.   
