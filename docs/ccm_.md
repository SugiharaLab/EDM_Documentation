
## <function> CCM </function> 
Convergent cross mapping between `columns` : `target`; and, reverse mapping between `target` : `columns`.

** Python **  :   
```python
CCM(dataFrame=None, columns='', target='', 
libSizes='', sample=0, E=0, Tp=0, knn=0, tau=-1, 
exclusionRadius=0, seed=0, embedded=False, 
includeData=False, noTime=False, ignoreNan=True,
verbose=False, showPlot=False, returnObject=False)
```

** R **  :   
```R
CCM(pathIn="./", dataFile="", dataFrame=NULL, E=0, 
Tp=0, knn=0, tau=-1, exclusionRadius=0,
columns="", target="", libSizes="", sample=0,
random=TRUE, seed=0, embedded=FALSE, includeData=FALSE,
parameterList=FALSE, verbose=FALSE, showPlot=FALSE, noTime=FALSE)
```

---

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: pandas DataFrame<br/>rEDM: data.frame | None|Input DataFrame| 
| columns | string or []| "" | Column name(s) for library | 
| target    | string | ""    | Prediction target column name |
| libSizes| string | ""      | CCM library sizes |
| sample    | int    | 0     | CCM number of random samples |
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 0     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set as E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius |
| seed      | unsigned | 0   | RNG seed, 0 = random seed |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| includeData| bool  | False | Include output statistics on all predictions |
| noTime    | bool | False | Do not require first data column of time or index |
| random    | bool   | True  | CCM use random samples? |
| parameterList | bool | False | Include parameter dictionary in return    |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 

<br/>
Refer to the [parameters](./parameters.md) table for general parameter definitions.

** Notes **  :  
Normally, one column and one target are specified.  The column time series is time-delay embedded to dimension `E`, then cross mapped with the target time series.  In a separate thread, the target time series is embedded to `E` and cross mapped against the column acting as the "target". 

If there are multiple `columns` and `embedded` is false, each column is time-delay embedded to dimension `E` creating an N-columns * E dimensional "mixed" embedding.  If `embedded` is true, no time-delay embedding is done, creating a multivariate embedding of the speficied columns.  The same logic applies if multiple target are specified for the "reverse" mapping. If embedded is false, each target is time-delay embedded to dimension `E` creating an N-target * E dimensional "mixed" embedding cross mapped to *only the first column* as the cross map target.  If `embedded` is true, no time-delay embedding is done, creating a multivariate embedding of the specified target(s).

`libSizes` is a list values or string of whitespace or comma separated library sizes.  If the string has 3 values, and, if the third value is less than the second value, the three values are interpreted as a sequence generator specifying "start stop increment" row values, i.e. "10 80 10" will evaluate library sizes from 10 to 80 in increments of 10.

Version 1.x: If `random` is true, sample observations are randomly selected 
from the subset of each library size. If `random` is false, sample is ignored 
and contiguous library rows up to the  current library size are used. Note 
this is *not* convergent cross mapping.  

If `seed=0` a random seed is generated for the random number generator. 
Otherwise, seed is used to initialise the random number generator.

** Returns **  :  
If `includeData` is `False`: returns DataFrame with 3 columns.   
The first column is `LibSize`, the second and third columns
are Pearson correlation coefficients for `column` : `target` 
and `target` : `column` cross mapping.

If `includeData` is `True`: returns a list with the above DataFrame
and a DataFrame of all Simplex projection statistics. If `parameterList = True`, a dictionary of `parameters` is added.

Version 2.x: If `returnObject = True` returns the CCM class object with all data and variables.
