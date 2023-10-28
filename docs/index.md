# Empirical Dynamic Modeling (EDM)

[Empirical dynamic modeling (EDM)](https://en.wikipedia.org/wiki/Empirical_dynamic_modeling) is an emerging non-parametric framework
for modeling nonlinear dynamic systems. EDM is based on the mathematical
theory of reconstructing attractor manifolds from time series data
([Takens 1981](https://en.wikipedia.org/wiki/Takens%27s_theorem)).
EDM algorithms include simplex projection
([Sugihara and May 1990](https://www.nature.com/articles/344734a0)),
S-map
([Sugihara 1994](https://royalsocietypublishing.org/doi/abs/10.1098/rsta.1994.0106)),
multivariate embedding
([Dixon, Milicich, and Sugihara 1999](https://science.sciencemag.org/content/283/5407/1528)),
convergent cross mapping
([Sugihara et al. 2012](https://science.sciencemag.org/content/338/6106/496)),
and multiview embedding
([Ye and Sugihara 2016](https://science.sciencemag.org/content/353/6302/922)).
These documents introduce the underlying theory, and illustrate analytical 
functionality with examples.  

The core EDM algorithms are implemented in the
[cppEDM library](https://github.com/SugiharaLab/cppEDM "cppEDM").
Python and R interfaces to the library are provided in the
[pyEDM](https://github.com/SugiharaLab/pyEDM "pyEDM") and
[rEDM](https://github.com/SugiharaLab/rEDM "rEDM") packages.  

------

## Motivation
Many analytic approaches use models as approximations of real world
systems to test hypotheses, explain mechanisms,
or, predict future outcomes. However, real world systems are
often nonlinear and multidimensional, rendering explicit parametric
equations problematic. Empirical models, which infer patterns and
associations from the data instead of using discrete, hypothesized
equations, represent a natural and flexible approach to modeling 
complex dynamics.  

------

## Foundations of EDM

###Time Series as Observations of a Dynamic System

<iframe width="100%" height="335"
src="https://www.youtube.com/embed/fevurdpiRYg"
frameborder="0" allow="autoplay; gyroscope; 
picture-in-picture" allowfullscreen></iframe>

Given a state space reconstructed via lagged embedding, or, from
multivariate observations, system prediction can be performed using
simplex or S-map projections. S-map (Sequentially Locally Weighted
Global Linear Maps) can also be used to assess variable interactions.
To infer causal relationships between variables,  Convergent Cross
Mapping (CCM) can be applied.  See the
[algorithms in depth section](./algorithms_in_depth) for details on
these functions.

------
