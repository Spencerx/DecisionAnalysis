<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Build Status](https://travis-ci.org/AFIT-R/DecisionAnalysis.svg?branch=master)](https://travis-ci.org/AFIT-R/DecisionAnalysis) [![Coverage Status](https://codecov.io/github/AFIT-R/DecisionAnalysis/coverage.svg?branch=master)](https://codecov.io/github/AFIT-R/DecisionAnalysis?branch=master) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/DecisionAnalysis)](https://cran.r-project.org/package=DecisionAnalysis) [![Downloads](http://cranlogs.r-pkg.org/badges/DecisionAnalysis)](http://cranlogs.r-pkg.org/badges/DecisionAnalysis) [![Total Downloads](http://cranlogs.r-pkg.org/badges/grand-total/DecisionAnalysis)](http://cranlogs.r-pkg.org/badges/grand-total/DecisionAnalysis)

DecisionAnalysis
----------------

Multi-Objective Decision Analysis is a process for making decisions when there are very complex issues involving multiple criteria and multiple parties who may be deeply affected by the outcomes of the decisions.

Using DecisionAnalysis allows individuals to consider and weight factors and trade-offs while evaluating each alternative. The individuals are then able to discuss the results and trade offs to help decide on a recommendation.

The DecisionAnalysis package contains all of the necessary functions required to :

1.  Plot a value hierarchy tree with weights
2.  Calculate and plot linear, exponential, and categorical single attribute value functions
3.  Calculate multiple attribute value function scores and plot their breakout
4.  Conduct sensitivity analysis

Installation
------------

The `DecisionAnalysis` package is currently in development and only available from GitHub, but can easily be installed using the [devtools](https://cran.r-project.org/web/packages/devtools/index.html) package:

    if (!requireNamespace("devtools")) install.packages("devtools")
    devtools::install_github("AFIT-R/DecisionAnalysis")
