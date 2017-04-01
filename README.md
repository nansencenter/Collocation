Collocation
===========

Errors are not necessarily independent in meteorological and oceanographic datasets.
The collocation method successfully accommodates errors in all variables of interest
(cf. https://en.wikipedia.org/wiki/Errors-in-variables_models) and is starting to
consider error dependence, but more modelling is needed.  This includes consideration
of, in particular, a collection of isolated samples and a much larger collection with
excellent coverage in space and/or time.  Typically, errors are dependent but given
appropriate error models, the relationship between variables can be quantified without
much restriction on their functional dependence (i.e., exploration can be guided by
geophysical wisdom, and apart from the error model itself, the only real limitation
is probably number of collocations).  In any case, it is convenient when filtering
data through an error model to focus on retrievals of regression slope (for an affine
model), signal, and (partly shared) noise, as all kinds of metrics can then be derived.
