# <function> Embed </function>

** Description **  :   
Creates a data block of Takens (1981) time-delay embedding from each of the 
columns in the csv file or dataFrame.  
The columns parameter can be a list of column names, or a list of 
column indices.   
Note: The returned DataFrame will have tau * (E-1) fewer 
rows than the input data from the removal of partial vectors as 
a result of the embedding.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| E         | int    | 0     | Data dimension | 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names | 
| verbose   | bool   | False | Echo messages |

** Returns **  :   
Constructed DataFrame with embedded columns.

# <function> Simplex </function> 
** Description **  :   
Simplex projection of the input data file or DataFrame.     
`nan` values are inserted in the output DataFrame where there is 
no observation or prediction.  
If embedded is false the data columns are embedded to dimension `E` with delay `tau`.  

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set as E+1)| 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| embedded  | bool   | False | Is data an embedding |
| const\_pred| bool   | False | Include non projected forecast data |
| verbose   | bool   | False | Echo messages |

** Returns **  :   
Constructed DataFrame with columns "Time", "Observations", and "Predictions".

# <function> SMap </function> 
** Description **  :   
SMap projection of the input data file or DataFrame. 
See the Parameters table for parameter definitions.  
nan values are inserted in the output DataFrame where there is 
no observation or prediction.  
If embedded is false the data columns are embedded to dimension E with delay tau .   
If predictFile is provided the predictions will be written to it in csv format.
If smapFile is provided the coefficients will be written to it in csv format.
If knn is not specified, it is set equal to the library size. 
If knn is specified, it must be greater than E .

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors | 
| tau       | int    | 1     | Embedding delay | 
| theta     | int    | 0     | SMap localization | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| columns   | string | ""    | Column names or indices for prediction | 
| target    | string | ""    | Target library column name or index |
| smapFile  | string | ""    | SMap coefficient output file |
| embedded  | bool   | False | Is data an embedding |
| const\_pred| bool   | False | Include non projected forecast data |
| verbose   | bool   | False | Echo messages |

** Returns **  :   
[Dict in `pyEDM`, named List in `rEDM`] with two DataFrames: {  
`predictions` [ 3 columns : "Time", "Observations", "Predictions"],  
`coefficients`[ 'E+2' columns : Time, and then 'E+1' SMap SVD fit coefficents]
}

# <function> CCM </function> 
Convergent cross mapping via Simplex of the first vector specified in columns 
against target . The data cannot be multivariable; the first vector in columns 
is time-delay embedded to dimension E.
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

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set as E+1)| 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| libSizes| string | ""      | CCM library sizes |
| sample    | int    | 0     | CCM number of random samples |
| random    | bool   | True  | CCM use random samples? |
| seed      | unsigned | 0   | RNG seed, 0 = random seed |
| verbose   | bool   | False | Echo messages |

** Returns **  :   
The returned DataFrame has 3 columns.   
The first column is `LibSize`, the second and third columns
are Pearson correlation coefficients for `column` : `target` 
and `target` : `column` cross mapping.

# <function> Multiview </function> 
** Description **  :   
Multiview embedding and forecasting of the input data file or DataFrame.   
See the Parameters table for parameter definitions.
`nan` values are inserted where there is no observation or prediction.
If `predictFile` is provided the Predictions will be written to it in csv format.
If `multiview` is not specified it is set to 'sqrt(C)' where C is the number of 
`E`-dimensional combinations out of all available data vectors.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set to E+1)| 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| multiview | int    | 0     | Multiview parameter : (if 0 then set to 'sqrt(C)' where C is the number of  E-dimensional combinations out of all available data vectors)|
| nthreads  | int    | 4     | Number of threads to use |


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
Note: nThreads defines the number of worker threads for the 10 embeddings. 
The maximum number of threads is 10.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| maxE      | int    | 10    | Evaluate embedding up to maxE | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| nthreads  | int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho |

** Returns **  :   
The returned DataFrame has columns `E` and `rho`.   

# <function> PredictInterval </function> 
** Description **  :   
Evaluate Simplex prediction skill for forecast intervals from 1 to 10.   
Used to evaluate prediction decay of system.  
Note: `nThreads` defines the number of worker threads for the 10 prediction 
interval forecasts. The maximum number of threads is 10.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| maxTp     | int    | 10    | Evaluate forecast with Tp up to maxTp | 
| E         | int    | 0     | Embedding dimension | 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| nthreads  | int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho |

** Returns **  :   
The returned DataFrame has columns `Tp` and `rho`. 

# <function> PredictNonlinear </function> 
** Description **  :   
Evaluate SMap prediction skill for localization parameter 
`theta`  (default from 0.01 to 9).   
`theta` is a string of theta values with a delimiter of [',', '\t', '\n'].
See the Parameters table for parameter definitions.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| theta     | string | ""    | `theta` is a string of theta values with a delimiter of [',' , '\t', '\n']. |
| E         | int    | 0     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | 1     | Embedding delay | 
| columns   | string | ""    | Column names for library| 
| target    | string | ""    | Target library column name |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| nthreads  | int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of theta vs Rho |

** Returns **  :   
The returned DataFrame has columns `theta` and `rho`. 

# <function> ComputeError </function> 
** Description **  :   
Compute Pearson correlation coefficient, maximum absolute error (MAE) 
and root mean square error (RMSE) between two vectors.

| Parameter | Type |  Purpose |
| --------- | ---- |  ------- |
| obsIn     | list |  Observations |
| predIn    | list |  Predictions |

** Returns **  :   
[Dict in `pyEDM`, named List in `rEDM`] with computed `rho`, `RMSE`, `MAE`.
