# EDM Algorithms 

## Simplex : Nearest Neighbor Projection

`Simplex` is a nearest neighbor projection. It locates the `knn` 
nearest neighbors to the query point (location in the state-space from
which a prediction is desired) within the library state-space. `knn` is
typically set to `E`+1, where `E` is the system dimension.  These `knn`
points define an `E`+1 dimensional simplex in the state-space.  The
prediction is computed as the average of the weighted state-space simplex
projected `Tp` points ahead.  Each neighbor is weighted
proportional to their distance to the query point as described in
[Sugihara and May 1990](https://www.nature.com/articles/344734a0).
`Simplex` is the most direct projection technique in the
EDM package, operates with minimal assumptions, and is the core algorithm
for the evaluation of embedding dimension
[`EmbedDimension()`](../edm_functions/#embeddimension), evaluation of
temporal forecast predictability
[`PredictInterval()`](../edm_functions/#predictinterval), 
convergent cross mapping [`CCM()`](../edm_functions/#ccm),
and multiview embedding [`Multiview()`](../edm_functions/#multiview).


## S-Map : Sequential Locally Weighted Global Linear Maps

S-Map extends the state-space prediction in `Simplex` from an
average of the `E`+1 knn neighbors, to a linear regression fit to all
neighbors, but localized with an exponential decay kernel as described
in [Sugihara 1994](https://royalsocietypublishing.org/doi/abs/10.1098/rsta.1994.0106). The exponential localization function is F(θ) = exp(-θd/D), where d
is the neighbor distance and D the mean distance.
In this way, neighbors close to the query point have a higher weight
than those further from it, such that a local linear approximation to
the nonlinear system can be reasonable. This _localization_ ability allows
one to identify an optimal local scale that may provide improved
predictability over a `Simplex` projection. Notably, assessing predictability
over a spectrum of localization parameters θ allows one to infer
state-dependence, and thus nonlinearity of the dynamics. See 
[`PredictNonlinear()`](../edm_functions/#predictnonlinear).

For a demonstration of S-Map state-space localization, see the
[S-MAP Notebook](./SMap_Demo.ipynb).

Another feature of S-Map is that for a properly fit model, the regression
coefficients between variables have been shown to approximate
the gradient (directional derivative) of variables along the manifold
([Deyle et al. 2016](https://royalsocietypublishing.org/doi/full/10.1098/rspb.2015.2258)). These Jacobians represent the time-varying interaction strengths
between system variables. 

## CCM : Convergent Cross Mapping

One of the corollaries to the Generalized Takens Theorem is that it
should be possible to cross predict or cross map between variables that
are observed from the same system. Suppose that in some dynamical system
involving variables _X_ and _Y_, _X_ causes _Y_. 
Since _X_ and _Y_ belong to the same dynamical system, their reconstructions
(via embeddings) _Mx_, and _My_, also map to the same system.

The causal variable _X_ leaves a signature on the affected variable _Y_,
and consequently, the reconstructed states based on _Y_ can be used to
cross predict the values of _X_. CCM leverages this property to infer
causality by predicting _X_ using _My_'s library of points (or vice versa
for the other direction of causality), while assessing improvements in
cross map predictability as larger and larger random samplings of _My_
are used. If the prediction skill of _X_ increases and saturates as the
entire _My_ is used, this provides evidence that _X_ is casually
influencing _Y_ as described in
[Sugihara et al. 2012](https://science.sciencemag.org/content/338/6106/496).

<iframe width="100%" height="335" src="https://www.youtube.com/embed/NrFdIz-D2yM" 
frameborder="0" allow="autoplay; gyroscope; picture-in-picture" allowfullscreen></iframe>  
