+++
# Software widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

# Order that this section will appear in.
weight = 30

+++

- [`simsurv`: Simulate Survival Data](https://cran.r-project.org/web/packages/simsurv/index.html) 

[`simsurv`](https://cran.r-project.org/web/packages/simsurv/index.html) is an [R](https://www.r-project.org) package for simulating survival (i.e. time-to-event) data. The user can simulate survival times from standard parametric survival distributions (exponential, Weibull, Gompertz), 2-component mixture distributions, or a user-defined hazard or log hazard function. The latter two features are those which likely separate the [`simsurv`](https://cran.r-project.org/web/packages/simsurv/index.html) package from other packages available for simulating survival data in [R](https://www.r-project.org/). The package implements the methods described in [Crowther and Lambert (2013)](http://onlinelibrary.wiley.com/doi/10.1002/sim.5823/abstract) and is modelled on the [`survsim`](http://www.stata-journal.com/article.html?article=st0275) package available in the Stata software.   

- [`rstanarm`: Bayesian Applied Regression Modeling via Stan](https://cran.r-project.org/web/packages/rstanarm/index.html)

[`rstanarm`](https://cran.r-project.org/web/packages/rstanarm/index.html) is an extensive [R](https://www.r-project.org) package for Bayesian applied regression modelling. It is written and maintained by [Ben Goodrich](http://www.columbia.edu/~bg2382/) and [Jonah Gabry](http://iserp.columbia.edu/people/jonah-gabry). However, I have contributed code for fitting multivariate mixed models (the `stan_mvmer` modelling function) and joint longitudinal and time-to-event models (the [`stan_jm`](https://cran.r-project.org/web/packages/rstanarm/vignettes/jm.html) modelling function), as well as a number of post-estimation functions for obtaining predictions and diagnostics for the fitted models.

- [`simjm`: Simulate Joint Longitudinal and Survival Data](https://github.com/sambrilleman/simjm) 

[`simjm`](https://github.com/sambrilleman/simjm) is an [R](https://www.r-project.org) package  package that allows the user to simulate data from a shared parameter joint model for longitudinal and time-to-event data. The shared parameter joint model from which the simulated data is generated is based on the model formulation described for the [`stan_jm`](https://cran.r-project.org/web/packages/rstanarm/vignettes/jm.html) modelling function in the [`rstanarm`](https://cran.r-project.org/web/packages/rstanarm/index.html) R package. The shared parameter joint model can be univariate (i.e. one longitudinal marker) or multivariate (i.e. more than one longitudinal marker) and a variety of parameterisations are allowed for the association structure between the longitudinal and event submodels.

- [`devr2`: Compute Cameron and Windmeijer's deviance based R-squared measure](https://ideas.repec.org/c/boc/bocode/s457340.html)

[`devr2`](https://ideas.repec.org/c/boc/bocode/s457340.html) is a [Stata](https://www.stata.com) module that can be used to calculate a deviance based R-squared measure for models estimated using Stata's `glm` command. The measure is based on the method of [Cameron and Windmeijer (1997)](https://www.sciencedirect.com/science/article/pii/S0304407696018180). The module can be easily installed from within your Stata session; simply type `ssc install devr2` into the Command window.
