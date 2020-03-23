## The EDM Framework
The EDM framework is predicated on the availability of a multidimensional
representation of the system dynamics.  For example, the well-known
[Rössler attractor](https://en.wikipedia.org/wiki/R%C3%B6ssler_attractor)
is a 3-dimensional (3-D) system that can express chaotic dynamics.
The set of 3 equations that define the Rössler system define an _attractor_
or _manifold_ defining the _state-space_ or _phase-space_ of the system. 
Often, one does not have complete information regarding the system
dynamics, in which case we can invoke Takens embedding theorem.

### Takens Theorem
[Takens theorem](https://en.wikipedia.org/wiki/Takens%27s_theorem) 
is a remarkable mathematical result that allows one to reconstruct a
representation of the system dynamics (state-space manifold) from a
single (univariate, 1-D) timeseries observed from the system.  The embedding
results in generation of a higher-dimensional representation of the system.

The process of creating this representation is termed _embedding_.  In the
EDM packages we can use the [`Embed()`](../edm_functions/#embeddimension)
function to create an embedding.  This function creates successively
time-lagged, if _τ_ < 0, or, time-advanced if _τ_ > 0, observation vectors
from the input vectors.  Embedding (with default _τ_ = -1) is performed
implicitly in EDM functions [`Simplex()`](../edm_functions/#simplex),
[`SMap()`](../edm_functions/#smap), and [`CCM()`](../edm_functions/#ccm),
unless the `embedded` argument is set `True` indicating that the data are
already embedded.

<!--- ![lorenz-logo](imgs/Lorenz_logo.png){: style="height:200px;width:200px"}--->

### Finding the optimal embedding dimension
In the case of the Rössler attractor we know that 3 dimensions will
best represent the system.  If Takens theorem is used to create an
embedding, there will exist an optimal number of dimensions that best represent
the dynamics.  We can estimate an optimal embedding dimension with the
[`EmbedDimension()`](../edm_functions/#embeddimension) function.
This function evaluates simplex prediction accuracy over a range of embedding
dimensions, the embedding dimension E with the highest predictive accuracy is
selected for system analysis.  This embedding is presumed to best represent
and "disentangle" the manifold.

### Nearerst Neighbor Forecasting: Simplex and S-map
EDM implements two timeseries prediction algorithms: Simplex, and S-map.
Both operate in the embedding state-space, using nearest neighbors
of a query point (location in the state-space from which a prediction is
desired) to project a new estimate along the manifold.

Simplex uses the centroid of the k-nearest neighbors (knn) of the query
point as the estimate.  The number of neighbors, knn, is conventionally
set as the number of dimensions plus one: knn = E + 1. 

S-map uses a linear regression of the query point to project a new
estimate along the manifold.  By default, number of neighbors knn in the
regression are set to the total number of state-space observation points.
An exponential localisation function (F(θ) = exp(-θd/D), where d is the
neighbor distance, D the mean distance) is used to selectively ignore
neighbors beyond the localisation radius.  This allows one to vary the
extent to which local neighbors are considered in the linear projection,
effectively modeling different local "resolutions" on the attractor.
The effect of this knn localisation can be assessed with the
[`PredictNonlinear()`](../edm_functions/#predictnonlinear) function that
evaluates S-map predictive skill over a range of localisations θ.

### Variable interactions
EDM also provides methods to assess interactions between state-space
variables, as well as inference of causal relationships.
[`SMap()`](../edm_functions/#smap) returns the regression coefficients
between variables, which have been shown to approximate the gradient
(directional derivative) of variables along the manifold
([Deyle et al. 2016](https://royalsocietypublishing.org/doi/full/10.1098/rspb.2015.2258)).

[`CCM()`](../edm_functions/#ccm) applies convergent cross mapping
to pairs of variables to infer possible causal links between variables.
Details on these algorithms are provided in the section
[EDM Algorithms in Depth](../algorithms_in_depth).
