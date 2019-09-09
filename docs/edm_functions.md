# <function> Embed </function>

Below are brief descriptions of the functions available in the pyEDM and rEDM
packages. See [general parameters](../general_parameters) 
for descriptions of the parameters used in these functions

** Description **  :   
Creates a data block of Takens (1981) time-delay embedding from each of the 
columns in the csv file or dataFrame.  
See the Parameters table for parameter definitions.  
The columns parameter can be a list of column names, or a list of 
column indices.   
If columns is a list of indices, then column names are created as V1, V2...  
Note: The returned DataFrame will have tau * (E-1) fewer 
rows than the input data from the removal of partial vectors as 
a result of the embedding.

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, E = 0, tau = 0, columns = "", 
verbose = False
```

** Returns **  :   
Constructed DataFrame with embedded columns.

# <function> Simplex </function> 
** Description **  :   
Simplex projection of the input data file or DataFrame.     
See the Parameters table for parameter definitions.   

nan values are inserted in the output DataFrame where there is 
no observation or prediction.  
If embedded is false the data columns are embedded to dimension E with delay tau .  
If embedded is true the data columns are assumed to be a multivariable data block.  

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",
lib = "", pred = "", E = 0, Tp = 1, knn = 0, tau = 1, columns = "", 
target = "", embedded = False, const_pred = False, verbose = False
```

** Returns **  :   
Constructed DataFrame with columns "Time", "Observations", and "Predictions".


# <function> SMap </function> 
** Description **  :   
SMap projection of the input data file or DataFrame. 
See the Parameters table for parameter definitions.  
nan values are inserted in the output DataFrame where there is 
no observation or prediction.  
If embedded is false the data columns are embedded to dimension E with delay tau .   
If embedded is true the data columns are assumed to be a multivariable data block.   
If predictFile is provided the predictions will be written to it in csv format.
If smapFile is provided the coefficients will be written to it in csv format.
If knn is not specified, it is set equal to the library size. 
If knn is specified, it must be greater than E .

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",
lib = "", pred = "", E = 0, Tp = 1, knn = 0, tau = 1, theta = 0,  
exclusionRadius = 0, columns = "",  target = "", smapFile = "",  
embedded = False, const_pred = False, verbose = False
```

** Returns **  :   
[Dict in `pyEDM`, named List in `rEDM`] with two DataFrames: {  
`predictions` - 3 columns : "Time", "Observations", "Predictions";  
`coefficients`- 'E+2' columns : Time, and then 'E+1' SMap SVD fit coefficents.  
}

# <function> CCM </function> 
** Description **  :   
Convergent cross mapping via Simplex of the first vector specified in columns against target . The
data cannot be multivariable, the first vector in columns is time-delay embedded to dimension E . See
the Parameters table for parameter definitions.

`libSizes` specifies a string with "start stop increment" 
row values, i.e. "10 80 10" will evaluate library sizes from 10 to 80 
in increments of 10.  
If `random` is true , sample observations are randomly selected from the 
subset of each library size.  
If seed=0 , then a random seed is generated for the random number generator. 
Otherwise, seed is used to initialise the random number generator.  
If `random` is false, sample is ignored and contiguous library rows up to the 
current library size are used.  
Note: Cross mappings are performed between column : target , and target : column . 

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",  
E = 0, Tp = 0, knn = 0, tau = 1, columns = "",  target = "", libSizes = "",   
sample = 0, random = True, seed = 0, verbose = False
```

** Returns **  :   
The returned DataFrame has 3 columns.   
The first column is `LibSize`, the second and third columns
are Pearson correlation coefficients for `column` : `target` 
and `target` : `column` cross mapping.

# <function> Multiview </function> 
** Description **  :   
Multiview embedding and forecasting of the input data file or DataFrame.   
See the Parameters table for parameter definitions.
nan values are inserted where there is no observation or prediction.
If `predictFile` is provided the Predictions will be written to it in csv format.
If `multiview` is not specified it is set to 'sqrt(C)' where C is the number of 
`E`-dimensional combinations out of all available data vectors.
If knn is not specified, it is set equal to E+1.

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",  
lib = "", pred = "", E = 0, Tp = 1, knn = 0, tau = 1, columns = "",  target = "",
multiview = 0, verbose = False, nThreads = 4
```

** Returns **  :   
[Dict in `pyEDM`, named List in `rEDM`] with two DataFrames: { 
Combo_rho, Predictions }
The `Predictions` DataFrame has 3 columns `Time`, `Observations`, `Predictions`.   
The `Combo_rho` DataFrame will have `E`+3 columns.   
The first `E` columns are the the column indices in the input data DataFrame 
that are embedded and applied to Simplex prediction.   
The last three columns are "rho", "MAE", "RMSE" corresponding to the prediction 
Pearson correlation, maximum absolute error and root mean square error.

# <function> EmbedDimension </function> 
** Description **  :   
Evaluate Simplex prediction skill for embedding dimensions from 1 to `maxE`.  
See the Parameters table for parameter definitions.  
Note: nThreads defines the number of worker threads for the 10 embeddings. 
The maximum number of threads is 10.

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",  
lib = "", maxE = 10, pred = "", Tp = 1, tau = 1, columns = "",  target = "",
embedded = False, verbose = True, nThreads = 4
```

** Returns **  :   
The returned DataFrame has columns `E` and `rho`.   

# <function> PredictInterval </function> 
** Description **  :   
Evaluate Simplex prediction skill for forecast intervals from 1 to 10.   
See the Parameters table for parameter definitions.  
Note: `nThreads` defines the number of worker threads for the 10 prediction 
interval forecasts. The maximum number of threads is 10.

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",  
lib = "", pred = "", maxTp = 10, tau = 1, columns = "", target = "",
embedded = False, verbose = True, nThreads = 4
```

** Returns **  :   
The returned DataFrame has columns `Tp` and `rho`. 

# <function> PredictNonlinear </function> 
** Description **  :   
Evaluate SMap prediction skill for localization parameter 
`θ`  (default from 0.01 to 9).   
`theta` is a string of theta values with a delimiter of [',', '\t', '\n'].
See the Parameters table for parameter definitions.

** Parameters **  :   
```python
pathIn = "", dataFile = "", dataFrame = None, pathOut = "", predictFile = "",  
lib = "", pred = "", theta = "", E = 0, Tp = 1, tau = 1,   
columns = "", target = "", embedded = False, verbose = True, nThreads = 4
```

** Returns **  :   
The returned DataFrame has columns `theta` and `rho`. 

# <function> ComputeError </function> 
** Description **  :   
Compute Pearson correlation coefficient, maximum absolute error (MAE) 
and root mean square error (RMSE) between two vectors.

** Parameters **  :   
```python
obsIn , predIn 
```

** Returns **  :   
[Dict in `pyEDM`, named List in `rEDM`] with computed `rho`, `RMSE`, `MAE`.
