# General Parameters

Many of the EDM functions use the same prediction engine, 
and so they share many of the following parameters. 
Please refer to the documentation according to the specific function
to verify which parameters are applicable as well as the default values 
(which can change from function to function).

## pathIn

* A string of the input data file path.

## datafile

* A string of the data file name.

## dataFrame

* The DataFrame containing the time series used to analyze/predict.
* In `pyEDM`, `dataFrame` should be a [pandas DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html).  
In `rEDM`, it is an R base type [data.frame](https://www.rdocumentation.org/packages/base/versions/3.6.1/topics/data.frame).


## lib

* The specified range of the time series of which to make our prediction from.
* A string of form `"x y"`, where x is the start index of the library 
and y is the end index of the library.

## pred

* Same format as `lib`, but specifies the portions of the time series to make
predictions for.

## E

* The embedding dimension to use for our attractor reconstruction.
* See the documentation for the [Embed](../edm_functions/#embed)
function for more details on embedding a variable with the `E` parameter. 

## tau

* The embedding delay (space between each lag index used). 
* See the documentation for the [Embed](../edm_functions/#embed)
function for more details on embedding a variable with the `tau` parameter. 

## Tp

The prediction interval (how many steps ahead to make forecasts).
* See the documentation for the [Embed](../edm_functions/#embed)
function for more details on embedding a variable with the `tau` parameter. 

## theta

* SMap localization weight parameter. 
* See the documentation for the [SMap](../edm_functions/#smap)
function for more details on how SMap uses the `tau` parameter. 

## knn

* The number of nearest neighbor used. 
* See the documentation for the [Simplex](../edm_functions/#simplex)
function for more details on how Simplex uses the `knn` parameter. 
* The default `knn` is `E+1` for Simplex and the entire library for SMap.

## exclusionRadius

* Prediction vector exclusion radius.
* Time points within a radius of `exclusionRadius` to the prediction point
will not be considered for the nearest neighbors search.

## verbose

* Flag to include warning messages or not.


