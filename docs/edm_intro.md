# The EDM Framework:

EDM is a toolkit for analyzing time series of nonlinear dynamical systems, 
with primary applications of forecasting, causal inference, and more.

The EDM framework leverages 
[Taken's theorem](https://en.wikipedia.org/wiki/Takens%27s_theorem) 
to better predict data and analyze the relationship between different variables 
of the system. Taken's theorem is relevantly powerful for these nonlinear, 
high-dimensional systems as rarely can we record all variables of a system, and 
the embedding allows us to reconstruct a shadow manifold containing relevant 
variables from a limited set of observers.



### Analysis begins with finding the optimal embedding dimension:
#### Finding the optimal embedding dimension:  
##### Why: 
[Taken's theorem](https://en.wikipedia.org/wiki/Takens%27s_theorem) states that
it is possible to reconstruct the attractor of a chaotic dynamical system from 
its observations. EDM analysis begins with finding the optimal embedding 
dimension, which is the number of lags on the input data that produces the 
highest prediction accuracy. Basically, by searching for the optimal embedding, 
we are trying to "organize" and "disentangle" this manifold, as well as recover 
some unrecorded actors on the system, such that our model can predict better.

##### How: 
We automate this optimal embedding search with the function 
[EmbedDimension](../edm_functions/#embeddimension). This function evaluates 
prediction accuracy on a range of embedding dimension. Pick the embedding 
dimension with the highest accuracy (rho) for future forecasting and system analysis, 
but prefer a lower embedding dimension if accuracy is comparable to the highest 
dimension's score. 

### To Simplex or to S-MAP?
Simplex and S-MAP are both prediction algorithms. For details on the 
algorithms, see the [EDM Algorithms in Depth](../algorithms_in_depth) 
section. The relevant gist is that Simplex is a more crude prediction algorithm 
than S-MAP, but useful as we are interested in simple prediction model that 
computes a general estimate of how well organized the attractor is for prediction, 
independent of the theta parameter for S-MAP.  
This function is primarily used to evaluate the embedding
dimension and in the CCM algorithm. S-Map is the more comprehensive 
prediction algorithm and should be used over Simplex for the most robust 
system prediction.

### S-MAP for Robust Predictions on Nonlinear Systems
The S-MAP algorithm's predictive success depends on the parameter theta used for
exponential weighting of state-space neighbors. For details on the algorithm
and how the theta parameter is used, see the
[EDM Algorithms in Depth](../algorithms_in_depth) section. Similar to how 
EmbedDimension is used to find the optimal embedding dimension parameter, 
the function  [PredictNonlinear](../edm_functions/#predictnonlinear) 
evaluates the prediction accuracy on a range of theta values.

### System analysis: 
In addition to analyzing how nonlinear the system of study is (via the 
`PredictNonlinear` function as we saw, EDM has a function `CCM`
(Convergent Cross Mapping) which analyzes the causal relationship between 
two observers of the system of study. This algorithm avoids the pitfalls of 
mirage correlation and causation without correlation. For details on the 
CCM algorithm, see the section [EDM Algorithms in Depth](../algorithms_in_depth).
