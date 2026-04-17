# Parameters

##### dataFrame
Input data frame. The columns must be named.<br>
The first column must be time index, strings or values unless `noTime = True`.

##### columns
String or vector of column name(s) in the input data used to create the library. If string then names must be whitespace separated.

##### target
String of column name in the input data used for prediction.

##### lib
String or vector with pairs of start and stop indices of input data rows used to create the library of E-dimensional embedding vectors. String indices must be whitespace separated. Note: Index values are _not_ 0-offset, index `1` is the first observation. 

##### pred
String or vector with pairs of start and stop indices of input data rows where predictions are made. String indices must be whitespace separated. Note: Index values are _not_ 0-offset, index `1` is the first observation. 

##### Tp
Prediction horizon (number of rows).

##### E
Embedding dimension.

##### tau
Time offset of embedding specified as number of time series rows. `tau` < 0 are lags, `tau` > 0 future values.

##### theta
In `Smap`: S-Map neighbor localization exponent. Single numeric.<br>
In `PredictNonlinear`: A whitespace delimeted string or numeric vector with values of S-map localization parameters to be evaluated.

##### knn
Number of nearest neighbors. If `knn=0`; `knn` is set to `E+1` for `Simplex()`; set to number of `lib` data rows for `SMap()`.

##### exclusionRadius
Excludes library vectors from the search space of nearest neighbors if their relative time index is within `exclusionRadius`. Note: only has meaning if `lib` and `pred` overlap. 

##### embedded
Logical specifying if the input data are an embedding. If `embedded = True` no emedding is performed, the input data are used as the embedding.  If `embedded = False`, all input data are embedded  to dimension `E` with time shift `tau`.

##### libSizes
String or vector of integers specifying CCM library sizes. If three values are provided, and, if the third value is less than the second, they are treated as a sequence generator specifying the intial library size; the final library size; and the library size increment. String values must be whitespace separated.

##### sample
Integer specifying the number of random samples to draw at each library size evaluation for CCM.

##### random
Logical to specify random (`True`) or sequential library sampling (`False`) in CCM. Only in version 1.x. 

##### replacement
Logical to specify sampling with replacement in CCM. Only in version 1.x. Not recommended.

##### includeData
Logical to return statistics on CCM sample(s). 

##### seed
Integer specifying the random sampler seed in CCM.  If `seed=0` a random seed is generated.

##### multiview
Number of multiview ensembles to average for the final prediction estimate in Multiview.

##### D
Multiview dimension.

##### trainLib
Use in-sample (`lib`=`pred`) prediction for multiview ranking

##### excludeTarget
Exclude `target` variable from multiviews 

##### maxE
Maximum value of `E` to evalulate in `EmbedDimension`.

##### maxTp
Maximum value of `Tp` to evalulate in `PredictInterval`.

##### numProcess
Number of parallel processes for computation in `EmbedDimension`; `PredictInterval` and `PredictNonlinear`.

##### mpMethod
Python multiprocessing context start method. 

##### chunksize
Python multiprocessing chunksize.

##### sequential
Before version 2.5: CCM flag to disable multiprocessing. 

##### parallel
Version 2.5: Boolean to enable/disable parallelization, or int specifying number of workers. 

##### pathIn
Filesystem path to input `dataFile`. CSV format.

##### dataFile
CSV format data file name. The first row must be column names.<br>
The first column must be time index, strings or values unless `noTime = True`.

##### solver
In pyEDM `SMap()`: An instance of a sklearn.linear_model object.

##### ignoreNan
Logical specifying whether data NaN values are to be ignored in `SMap`: default `True`. 

##### noTime
Logical indicating whether input data lack a time vector in first column: default `False`.

##### validLib
Conditional embedding. Boolean vector identifying time series rows whose  corresponding embedding vectors define the state-space library.

##### generateSteps
Generative feedback predictions for `Simplex()` or `SMap()`.

##### verbose
Logical to produce additional console reporting.

##### showPlot
Logical to plot results (pyEDM & rEDM).
