
## <function> MakeBlock </function>
** Description **  :
Creates a data block of time-delay embedding from each of the
columnNames in the dataFrame.

** Python **  :   
```python
MakeBlock(dataFrame, E=0, tau=-1, columnNames=[], deletePartial=False)
```

** R **  :   
```R
MakeBlock(dataFrame, E = 0, tau = -1, columns = c(), deletePartial = FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame |None|Input DataFrame|
| E         | int    | 0     | Data dimension |
| tau       | int    | -1    |Embedding shift. Negative: lag, positive: future|
| columnNames  | []  | ""    | List of column names  |
| deletePartial| bool| False | Remove rows with NaNs from embedding |

<br/>
** Notes **  :
Refer to the [parameters](./parameters.md) table for general parameter definitions.

The `columnNames` is a list of column names.

The time column is not included in the returned DataFrame.

The `MakeBlock` function is a low level function that does not perform
error checking.  The `Embed` function provides error checking and file-based
input.

** Returns **  :
DataFrame with embedded columns.
