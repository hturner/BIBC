# Uses of gnm for Generalized (Non)linear Modelling

A keynote talk for [Biometrics in the Bush Capital (BIBC2025)](https://biometricsociety.org.au/conference2025).

## Abstract

The R package {gnm} was designed as a unified interface to fit Generalized Nonlinear Models: _generalized_ to handle responses with restricted range and/or a variance that depends on the mean, and _nonlinear_ to allow the predictor for the mean to be nonlinear in its parameters. This framework covers several models that were proposed in the literature and adopted in practice before {gnm} was released, but used to require a mixed bag of specialised software to fit.

With {gnm} celebrating its 20th birthday this year, it's a good time to review how the package is being used. I'll highlight some of the applications we were aware of when {gnm} was first developed, that remain in common use, and explore more recent applications, particularly in the field of biometrics.

We'll discover one motivation for using {gnm}, is for the "eliminate" feature that efficiently estimates stratification parameters. This can be useful even when the predictor is linear, as in the case of using conditional Poisson models to analyse case-crossover studies in epidemiology.  We'll also look at two of the packages that have built on {gnm}. The first, {multgee}, uses {gnm} to fit multiplicative interactions for certain correlation structures when modelling categorical data, with applications in public health, agriculture, and psychology. The second, {VFP}, is a more specialised package that uses {gnm} to model the mean-variance relationship for in-vitro diagnostic assays. 

Through these use cases we'll see how different features of {gnm} can be applied, demonstrating the versatility of this software.
