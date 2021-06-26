# API Reference

## <function> Simplex </function> 
** Description **  :   
Simplex projection of the input data file or DataFrame.

If `embedded` is false (default) the data columns are embedded to dimension `E` with time shift `tau`.  If `knn` = 0, it is set to E+1.

`validLib` implements conditional embedding (CE). It is a boolean vector the same length as the number of time series rows. A `false` entry means that the state-space vector derived from the corresponding time series row will not be included in the state-space library. See [`examples`](./cond_emb_demo.ipynb).

`nan` values are inserted in the output DataFrame where there is 
no observation or prediction.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame|
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set to E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows)| 
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding? If False, embed to E|
| const\_pred| bool  | False | Include non projected forecast data |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| validLib  | bool [] | [] or None | Condtional embedding |

<br/>
** Returns **  :   
DataFrame with columns : "Time", "Observations", "Predictions".

## <function> SMap </function> 
** Description **  :   
SMap projection of the input data file or DataFrame.

If `embedded` is false, data columns are embedded to dimension E with shift tau.
If `predictFile` is provided the predictions are written in csv format.
If `smapFile` is provided the coefficients are written in csv format.
If `knn` is not specified, it is set equal to the library size. 
If `knn` is specified, it must be greater than `E`.

`nan` values are inserted in the output DataFrame where there is 
no observation or prediction.

`validLib` implements conditional embedding (CE). It is a boolean vector the same length as the number of time series rows. A `false` entry means that the state-space vector derived from the corresponding time series row will not be included in the state-space library. See [`examples`](./cond_emb_demo.ipynb).

** Note ** :   
`SMap` should be called with columns explicitly corresponding to
dimensions `E`. In the univariate case (number of `columns` = 1) with
default `embedded = false`, the time series will be time-delay
embedded to dimension `E`, `SMap` coefficients correspond to each dimension. 

If a multivariate data set is used (number of `columns` > 1) it
must use `embedded = true` with `E` equal to the number of columns.
This prevents the function from internally time-delay embedding the
multiple columns to dimension `E`.  If internal time-delay embedding
were performed, then state-space columns will not correspond to the
intended dimensions in the matrix inversion, coefficient assignment,
and prediction.  In this multivariate case, the user can first prepare
the embedding (using [`Embed()`](../edm_functions/#embed) for time-delay
embedding if desired, add a first column of time), then pass this embedding 
to `SMap` with appropriately specified `columns`, `E`, and `embedded = true`.

In PyEDM: The default LAPACK SVD solver `dgelss()` can be replaced with
a class object instantiated from the `sklearn.linear_model` class.
Supported solvers include `LinearRegression`, `Ridge`, `Lasso`,
`ElasticNet`, `RidgeCV`, `LassoCV`, `ElasticNetCV`. See [`examples`](./solvers_demo.ipynb). 

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame|
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| theta     | int    | 0     | SMap localization | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name or index |
| smapFile  | string | ""    | SMap coefficient output file |
| solver    | sklearn.linear_model | None | Linear system solver |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| const\_pred| bool  | False | Include non projected forecast data |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |
| validLib  | bool [] | [] or None | Conditional embedding |

<br/>
** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with two DataFrames:<br/>
`predictions` [ 3 columns : "Time", "Observations", "Predictions"],<br/>
`coefficients`[ E+2 columns : "Time", and E+1 SMap coefficents]<br/>

## <function> CCM </function> 
Convergent cross mapping of the first vector specified in columns 
against target.

The data cannot be multivariable; the first vector in columns 
is time-delay embedded to dimension `E` with time shift `tau`.  

`libSizes` specifies a string  of whitespace or comma separated library sizes.  If the string has 3 values, and, if the third value is less than the second value, then the three values are interpreted as a sequence generator specifying "start stop increment" row values, i.e. "10 80 10" will evaluate library sizes from 10 to 80 in increments of 10.

If `random` is true, sample observations are randomly selected from the 
subset of each library size.

If `random` is false, sample is ignored and contiguous library rows up to the 
current library size are used.  

If `seed=0` , then a random seed is generated for the random number generator. 
Otherwise, seed is used to initialise the random number generator.

Note: Cross mappings are performed between `column` : `target`; and, the reverse mapping between `target` : `column`.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 0     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set as E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| columns | string or []| "" | Column name for library | 
| target    | string | ""    | Prediction target column name |
| libSizes| string | ""      | CCM library sizes |
| sample    | int    | 0     | CCM number of random samples |
| random    | bool   | True  | CCM use random samples? |
| replacement | bool | False | CCM random sample with replacement? |
| seed      | unsigned | 0   | RNG seed, 0 = random seed |
| includeData| bool  | False | Include output statistics on all predictions |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |

<br/>
** Returns **  :  
If `includeData` is `False`: returns DataFrame with 3 columns.   
The first column is `LibSize`, the second and third columns
are Pearson correlation coefficients for `column` : `target` 
and `target` : `column` cross mapping.

If `includeData` is `True`: returns a list with the above DataFrame
and a DataFrame of all Simplex projection statistics. 

## <function> Multiview </function> 
** Description **  :   
Multiview embedding and forecasting of the input data file or DataFrame.

See the Parameters table for parameter definitions.

`nan` values are inserted where there is no observation or prediction.

If `predictFile` is provided the Predictions will be written to it in csv format.

If `multiview` is not specified it is set to 'sqrt(C)' where C is the number of 
`D`-dimensional combinations out of all available data vectors.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| D         | int    | N cols| Multiview state-space dimension | 
| E         | int    | 1     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors (if 0 then set to E+1)| 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target library column name |
| multiview | int    | 0     | Multiview parameter : (if 0 then set to 'sqrt(C)' where C is the number of  D-dimensional combinations out of all available data vectors)|
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| trainLib  | bool   | True  | Use in-sample (lib=pred) prediction for ranking |
| excludeTarget | bool | False | Exclude target variable from multiviews |
| numThreads| int    | 4     | Number of threads to use |
| verbose   | bool   | False | Echo messages |
| showPlot  | bool   | False | Plot results (pyEDM, rEDM) |

<br/>
** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with two DataFrames:<br/>
View<br/>
Predictions<br/>

The `Predictions` DataFrame has 3 columns: `Time`, `Observations`, `Predictions`.   
The `View` DataFrame has `E`+3 columns.   
The first `E` columns are the the column indices in the input data DataFrame 
that are embedded and applied to Simplex prediction.   
The last three columns are "rho", "MAE", "RMSE" corresponding to the prediction 
Pearson correlation, maximum absolute error and root mean square error.

## <function> EmbedDimension </function> 
** Description **  :   
Evaluate Simplex prediction skill for embedding dimensions from 1 to `maxE`.

Note: nThreads defines the number of worker threads for the 10 embeddings. 
The maximum number of threads is 10.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| maxE      | int    | 10    | Evaluate embedding up to maxE | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding |
| verbose   | bool   | False | Echo messages |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |

<br/>
** Returns **  :   
DataFrame with columns `E` and `rho`.   

## <function> PredictInterval </function> 
** Description **  :   
Evaluate Simplex prediction skill for forecast intervals from 1 to maxTp.

Note: `nThreads` defines the number of worker threads for the 10 prediction 
interval forecasts. The maximum number of threads is 10.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| maxTp     | int    | 10    | Evaluate forecast with Tp up to maxTp | 
| E         | int    | 0     | Embedding dimension | 
| tau       | int    | -1    | Embedding shift (time series rows) | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding?  |
| verbose   | bool   | False | Echo messages |
| numThreads| int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of E vs Rho (pyEDM, rEDM) |

<br/>
** Returns **  :   
DataFrame with columns `Tp` and `rho`. 

## <function> PredictNonlinear </function> 
** Description **  :   
Evaluate SMap prediction skill for localization parameter 
`theta`  (default from 0.01 to 9).

`theta` is a string of theta values with a delimiter of [',', '\t', '\n'].
See the Parameters table for parameter definitions.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib   | string or [] | ""  | Pairs of library start stop row indices |
| pred  | string or [] | ""  | Pairs of prediction start stop row indices |
| theta     | string | ""    | `theta` is a string of theta values with a delimiter of [',' , '\t', '\n']. |
| E         | int    | 0     | Embedding dimension | 
| Tp        | int    | 1     | Prediction Interval | 
| tau       | int    | -1    | Embedding time shift (time series rows) | 
| columns | string or []| "" | Column names for library | 
| target    | string | ""    | Prediction target column name |
| embedded  | bool   | False | Is data an embedding? If False, embed to E |
| verbose   | bool   | False | Echo messages |
| nthreads  | int    | 4     | Number of threads to use |
| showPlot  | bool   | True  | Show plot of theta vs Rho |

<br/>
** Returns **  :   
DataFrame with columns `theta` and `rho`. 

## <function> Embed </function>
** Description **  :
Creates a data block of time-delay embedding from each of the 
columns in the csv file or dataFrame.  

The columns parameter can be a list of column names, a list of 
column indices, or a whitespace separated string of column names or indices.

Note: The `MakeBlock` function can be called with `deletePartial = True` 
to return a DataFrame with |tau| * (E-1) rows of partial vectors removed
(rows with NaNs) as a result of the embedding. 

Note: The time column is not included in the returned DataFrame.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path |
| dataFile  | string | ""    | Data file name |
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame|
| E         | int    | 0     | Data dimension | 
| tau       | int    | -1    |Embedding shift. Negative: lag, positive: future|
| columns   | string or [] | "" | Column names  |
| verbose   | bool   | False | Echo messages |

<br/>
** Returns **  :   
DataFrame with embedded columns.

## <function> MakeBlock </function>
** Description **  :
Creates a data block of time-delay embedding from each of the
columnNames in the dataFrame.

The `columnNames` is a list of column names.

Note: The time column is not included in the returned DataFrame.

Note: The `MakeBlock` function is a low level function that does not perform
error checking.  The `Embed` function provides error checking and file-based
input.

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame |None|Input DataFrame|
| E         | int    | 0     | Data dimension |
| tau       | int    | -1    |Embedding shift. Negative: lag, positive: future|
| columnNames  | []  | ""    | List of column names  |
| deletePartial| bool| False | Remove rows with NaNs from embedding |

<br/>
** Returns **  :
DataFrame with embedded columns.

## <function> ComputeError </function> 
** Description **  :   
Compute Pearson correlation coefficient, maximum absolute error (MAE)
and root mean square error (RMSE) between two vectors.

| Parameter | Type |  Purpose |
| --------- | ---- |  ------- |
| obsIn     | list |  Observations |
| predIn    | list |  Predictions |

<br/>
** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with computed `rho`, `RMSE`, `MAE`.
