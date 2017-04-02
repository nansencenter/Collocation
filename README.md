Collocation
===========

Errors are not necessarily independent in meteorological and oceanographic datasets.
The collocation method (cf. http://www.sciencedirect.com/science/article/pii/S0303243415300258)
successfully accommodates errors in all variables of interest
(cf. https://en.wikipedia.org/wiki/Errors-in-variables_models) and is starting to
accommodate error dependence, but more modelling is needed.  This need includes, in
particular, consideration of a collection of isolated samples and a collection of more
distributed samples in space and/or time.  Typically, errors are dependent but given
appropriate error models, the relationship between variables can be quantified without
much restriction on their functional dependence (i.e., exploration can be guided by
geophysical wisdom, and apart from a specification of the error model itself, the only
real limitation is probably just the number of collocations).  In any case, it is
convenient when filtering data through an error model to focus on retrievals of
regression slope (for an affine model), signal, and (partly shared) noise, as all
kinds of metrics can then be derived.
