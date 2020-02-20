# Parameters

| Parameter | Description |
| --------- | ----------- |
pathIn      |Filesystem path to input `dataFile`. CSV format.
dataFile    |CSV format data file name. The first column must be a timeindex or time values. The first row must be column names.
dataFrame   | Input data.frame. The first column must be a time index or time values. The columns must be named.
pathOut     | Filesystem path for `predictFile` containing output predictions.
predictFile |Observation and Prediction output file name. CSV format.
lib         |String with start and stop indices of input data rows used to create the library of observations. A single contiguous range is supported. `rEDM` accepts a 2-vector. 
pred        |String with start and stop indices of input data rows used for predictions. A single contiguous range is supported. `rEDM` accepts a 2-vector. 
E           |Embedding dimension.
Tp          |Prediction horizon (number of time column rows).
knn         |Number of nearest neighbors. If knn=0; knn is set to E+1 for Simplex(); set to number of lib data rows for SMap().
tau         |Lag of time delay embedding specified as number of time column rows.
theta       |In Smap: S-Map neighbor localisation exponent. Single numeric.
theta       |In PredictNonlinear: A whitespace delimeted string with values of S-map localisation parameters to be evaluated.
exclusionRadius|Excludes vectors from the search space of nearest neighbors if their relative time index is within exclusionRadius.
columns     |String of whitespace separated column name(s) in the input data used to create the library.
target      |String of column name in the input data used for prediction.
smapFile    |Output file containing S-map coefficients.
embedded    |Logical specifying if the input data are embedded.
libSizes    |String of 3 whitespace separated integer values specifying the intial library size; the final library size; and the library size increment for CCM.
sample      |Integer specifying the number of random samples to draw at each library size evaluation for CCM.
random      |Logical to specify random (`True`) or sequential library sampling (`False`) in CCM.
replacement |Logical to specify sampling with replacement in CCM.
seed        |Integer specifying the random sampler seed in CCM.  If `seed=0`, then a random seed is generated.
multiview   |Number of multiview ensembles to average for the final prediction estimate in Multiview.
maxE        |Maximum value of E to evalulate in EmbedDimension.
maxTp       |Maximum value of Tp to evalulate in PredictInterval.
numThreads  |Number of parallel threads for computation in EmbedDimension; PredictInterval and PredictNonlinear.
verbose     |Logical to produce additional console reporting.
const_pred  |Logical to add a _constant predictor_ column to the output. The constant predictor is X(t+1) = X(t).
showPlot    |Logical to plot results.
