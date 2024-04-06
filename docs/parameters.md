# Parameters

##### dataFrame
Input data.frame. The columns must be named.<br>
The first column must be time index, strings or values unless `noTime = True`.

##### columns
String or vector of column name(s) in the input data used to create the library. String names must be whitespace separated.

##### target
String of column name in the input data used for prediction.

##### lib
String or vector with pairs of start and stop indices of input data rows used to create the library of E-dimensional embedding vectors. String indices must be whitespace separated.

##### pred
String or vector with pairs of start and stop indices of input data rows<br>
where predictions are made. String indices must be whitespace separated.

##### Tp
Prediction horizon (number of time column rows).

##### E
Embedding dimension.

##### tau
Time offset of embedding specified as number of time series rows. `tau` < 0 are lags, `tau` > 0 future values.

##### theta
In `Smap`: S-Map neighbor localisation exponent. Single numeric.<br>
In `PredictNonlinear`: A whitespace delimeted string or numeric vector with  values of S-map localisation parameters to be evaluated.

##### knn
Number of nearest neighbors. If `knn=0`; `knn` is set to `E+1` for `Simplex()`; set to number of `lib` data rows for `SMap()`.

##### exclusionRadius
Excludes library vectors from the search space of nearest neighbors if their relative time index is within `exclusionRadius`.

##### embedded
Logical specifying if the input data are embedded.  If `embedded = True`, no emedding is performed.  If `embedded = False`, all input data are embedded  to dimension `E` with time shift `tau`.

##### libSizes
String or vector of integers specifying CCM library sizes. If three values are provided, and, if the third value is less than the second, they are treated as a sequence generator specifying the intial library size; the final library size; and the library size increment. String values must be whitespace separated.

##### sample
Integer specifying the number of random samples to draw at each library size evaluation for CCM.

##### random
Logical to specify random (`True`) or sequential library sampling (`False`) in CCM.

##### replacement
Logical to specify sampling with replacement in CCM. Not recommended.

##### includeData
Logical to return all CCM projection data frames.

##### seed
Integer specifying the random sampler seed in CCM.  If `seed=0`, then a random seed is generated.

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

##### numThreads
Number of parallel threads for computation in `EmbedDimension`; `PredictInterval` and `PredictNonlinear`.

##### pathIn
Filesystem path to input `dataFile`. CSV format.

##### dataFile
CSV format data file name. The first row must be column names.<br>
The first column must be time index, strings or values unless `noTime = True`.

##### pathOut
Filesystem path for `predictFile` containing output predictions.

##### predictFile
Observation and Prediction output file name. CSV format.

##### smapCoefFileSMap
Coefficient output file name. CSV format.

##### smapSVFile
`SMap` singular value output file name. CSV format.

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

##### parameterList
Add parameter dictionary to return objects in `Simplex()`,`SMap()`,`CCM()`,`Multiview()`.

##### verbose
Logical to produce additional console reporting.

##### const_pred
Logical to add a constant predictor column to the output.  The constant predictor is X(t+1) = X(t).

##### showPlot
Logical to plot results (pyEDM & rEDM).
