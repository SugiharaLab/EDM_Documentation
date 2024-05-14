
## <function> Embed </function>
** Description **  :
Creates a data block of time-delay embedding from each of the 
columns in the csv file or dataFrame.  

** Python **  :   
```python
Embed(dataFrame=None, E=0, tau=-1, columns='', 
includeTime=False, pathIn='./', dataFile=None, )
```

** R **  :   
```R
Embed(path = "./", dataFile = "", dataFrame = NULL, E = 0, 
tau = -1, columns = "", verbose = FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame|
| E         | int    | 0     | Data dimension | 
| tau       | int    | -1    |Embedding shift. Negative: lag, positive: future|
| columns   | string or [] | "" | Column names  |
| pathIn    | string | "./"  | Input data file path |
| dataFile  | string | ""    | Data file name |
| includeTime| bool  | False | Include time vector in output |

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :   
The `columns` parameter can be a list of column names, a list of 
column indices, or a whitespace separated string of column names or indices.

Version 1.x: The time column is not included in the returned DataFrame.

Version 2.x: The time column is included in the returned DataFrame
if `includeTime = True`. 

** Returns **  :   
DataFrame with embedded columns.
