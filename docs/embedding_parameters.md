# Embedding

The [`EDM Framework`](../edm_intro) is based on a multidimensional representation of system dynamics, colloquially referred to as an _embedding_.  Given a dynamical system of dimension D, the [Whitney Embedding Theorem](https://en.wikipedia.org/wiki/Whitney_embedding_theorem#See_also) establishes limits on the embedding dimension, E, needed to completely represent the dynamics. Generally, EDM uses the parameter E to represent the dimension of the embedding, however, to support multivariate embeddings there are deviations from the above definitions as noted below.

The combination of the `columns` and  `embedded` parameters control what
variables are included in the embedding, and, whether a time-delay embedding
is created.  The default `embedded = false` instructs EDM to create a
time-delay embedding using each variable in `columns`.  If  `embedded = true`,
the set of variables specified in `columns` is assumed to be a valid embedding,
no time-delay embedding is performed. 

These functions accept multiple values for the `columns` parameter: 
[`Embed()`](../edm_functions/#embed)
[`PredictInterval()`](../edm_functions/#predictinterval)
[`PredictNonlinear()`](../edm_functions/#predictnonlinear)
[`Simplex()`](../edm_functions/#simplex)
[`SMap()`](../edm_functions/#smap)
[`Multiview()`](../edm_functions/#multiview)

These functions accept the `embedded` parameter:
[`PredictInterval()`](../edm_functions/#predictinterval)
[`PredictNonlinear()`](../edm_functions/#predictnonlinear)
[`Simplex()`](../edm_functions/#simplex)
[`SMap()`](../edm_functions/#smap)

- If `embedded = false` (default):
    - If `columns` is a single value, then an E-dimensional time-delay 
    embedding is created.  
    - If `columns` has N values, then each of the N column variables 
    is time-delay embedded to dimension E.  The EDM state-space has overall 
    dimension E*N.
    
- If `embedded = true`:
    - The EDM state-space has dimension E = N, the number of `columns`.
    
## Examples

1. `Simplex( ..., columns = 'x', E = 2 )` : 2-dimensional univariate embedding.
2. `Simplex( ..., columns = 'x y', E = 2 )` : 4-dimensional multivariate 
embedding.
3. `Simplex( ..., columns = 'x y', E = 2, embedded = True )` : 2-dimensional 
multivariate embedding.

## CCM()
`CCM()` only operates on the first column, other entries in columns are ignored.
E is the time-lag embedding dimension applied to the first column.

## Multiview()
`Multiview()` has parameters `D`, `E`, `multiview`.

* `D` is the dimension of the state-space processed by simplex in each 
multivariate evaluation. `D` defaults to the number of columns.

* `E` is the embedding dimension of each variable. If `E` = 1, no time
delay embedding is done, the state-space is the `D` columns.  If `E` > 1,
then each of the `D` columns are embedded to `E`, however, the state-space
remains D-dimensional as combinations of the embeddings are evaluated 
D-at-a-time.

* `multiview` is the number of top-ranked D-dimensional predictions to
average for the final prediction. Default `multiview` = sqrt(C) where C
is the number of combinations C(n,D) available from the n = D * E variables
taken D at-a-time.

## SMap()
`SMap()` should be called with `columns` explicity corresponding to
dimensions `E`.  In the multivariate case (number of `columns` > 1)
use `embedded = true` with `E` equal to the number of `columns`.
See the note in [`SMap() documentation`](../edm_functions/#smap).
