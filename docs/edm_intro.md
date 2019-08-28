# A Beginners Guide to Using EDM 

EDM is a toolkit for analyzing time series of nonlinear dynamical systems, 
with primary applications of forecasting, causal inference, and more.


## High level EDM Workflow :
### System prediction : 
Typically we start our analysis with the [Simplex]("") function to find 
the optimal embedding dimension of our data. Conveniently, we can use the
[EmbedDimension]("") function to automate this trial and error of varying
`E` to find the best `rho` value. Note the `E` corresponding to the highest 
`rho` value, but prefer a lower embedding dimension if there are close `rho` 
values.   
We typically only use Simplex to find the embedding dimension as it is fast but
[SMap]("") predicts better for nonlinear systems.  
Next we will investigate how nonlinear the system is and find the 
best `theta` value for SMap. SMap uses the `theta` value to give points closer
to the query point on the system manifold higher weight in our prediction. You
can learn more about SMap and how it uses `theta` [here](""). Use the 
[PredictNonlinear]("") function to determine the `theta` value with the 
highest prediction value. If the prediction accuracy increases with `theta`, 
the system is identified to have state dependence (nonlinearity) to a degree
proportional to `theta`.  
You can optionally investigate the prediction decay with the 
[PredictInterval]("") function.   
Now you can use SMap with your optimally found arguments to perform the 
system prediction. Use the [SMap]("") function to perform the prediction.   

### System analysis : 
To study the optimal embedding dimension and the degree of 
nonlinearity of your data, read the [System Prediction]("") introduction on 
using the functions [EmbedDimension]("") and [PredictNonlinear]("").  
To study the causal relationships between two observers of your system, we use 
the [CCM]("") (Convergent Cross Mapping) function. We use CCM rather than 
correlation analysis to avoid mistaking [mirage correlation]("") for causality 
and for the fact that [causation does not necessarily imply correlation](""). 
CCM basically evaluates a [Granger Causality]("") test for two time series 
variables to evaluate causality in both directions. 


