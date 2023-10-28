
## <function> Embed </function>
** Description **  :
Creates a data block of time-delay embedding from each of the 
columns in the csv file or dataFrame.  

** Python **  :   
```python
Embed(pathIn='./', dataFile='', dataFrame=None, E=0,
tau=-1, columns='', verbose=False)
```

** R **  :   
```R
Embed(path = "./", dataFile = "", dataFrame = NULL, E = 0, 
tau = -1, columns = "", verbose = FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path |
| dataFile  | string | ""    | Data file name |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame|
| E         | int    | 0     | Data dimension | 
| tau       | int    | -1    |Embedding shift. Negative: lag, positive: future|
| columns   | string or [] | "" | Column names  |
| verbose   | bool   | False | Echo messages |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
The `columns` parameter can be a list of column names, a list of 
column indices, or a whitespace separated string of column names or indices.

The `MakeBlock` function can be called with `deletePartial = True` 
to return a DataFrame with |`tau`| * (`E`-1) rows of partial vectors removed
(rows with NaNs) as a result of the embedding. 

The time column is not included in the returned DataFrame.

** Returns **  :   
DataFrame with embedded columns.
