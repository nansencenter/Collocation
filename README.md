Collocation
===========

Errors are not necessarily independent in meteorological and oceanographic datasets.
The collocation method successfully accommodates errors in all variables of interest
(cf. https://en.wikipedia.org/wiki/Errors-in-variables_models) and is starting to
consider error dependence, but more modelling is needed.  This includes consideration
of, in particular, a collection of isolated samples and a much larger collection with
excellent coverage in space and/or time.  Corresponding errors are typically not
independent, unfortunately, but given appropriate error models, relationships between
variables can be quantified without any restriction on the functional dependence of
such relationships (i.e., exploration can be guided by geophysical wisdom, but apart
from the error model itself, the only real limitation is probably number of available
collocations).  In any case, it is convenient when casting or filtering data through
an error model to focus retrievals on regression slope (for an affine model) and the
correspoding signal and noise, as all kinds of metrics can then be derived.
