+++
title = "Software"
author = ["Mark S. Handcock"]
draft = false
+++

-   [RDS Analyst](http://wiki.stat.ucla.edu/hpmrg/index.php/RDS_Analyst_Install) is a software
package for the analysis of Respondent-driven sampling (RDS) data that
implements recent advances in statistical methods. RDS Analyst has an
easy-to-use graphical user interface to the powerful and sophisticated
capabilities of the computer package R. It provides a comprehensive
framework for working with RDS data, including tools for sample and
population estimations, testing, confidence intervals and sensitivity
analysis.

-   For more information on Relative Distribution Methods, including the preface
to the book, data sets, and software to implement the methods are
available from the [Relative Distribution
website](https://github.com/handcock/reldist).

-   For
more information on [R](http://www.r-project.org/) software to implement
the statistical methods described in the paper *Resource utilization by
an avian nest predator: relating resources to a probabilistic measure of
animal space use*, by John M. Marzluff, J. J. Millspaugh, P.
Hurvitz, and Mark S. Handcock, *Ecology*, 2004, 85:1411-1427,
see the [Resource Utilization Function Estimation
website](https://github.com/handcock/ruf).

-   The
[R](http://www.r-project.org/) software package
[statnet](http://statnet.org): software tools for the representation,
visualization, analysis and simulation of social network data.

-   The
[R](http://www.r-project.org/) software package
[[latentnet]](http://cran.r-project.org/web/packages/latentnet):
software to fit and evaluate latent position and cluster models for
statistical networks.

-   The
[R](http://www.r-project.org/) software package
[[networksis]](http://cran.r-project.org/web/packages/networksis):
A Package to Simulate Bipartite Graphs with Fixed Marginals through
Sequential Importance Sampling.

-   The
[R](http://www.r-project.org/) software package
[[ergm]](http://cran.r-project.org/web/packages/ergm): A
Package to Fit, Simulate and Diagnose Exponential-Family Models for
Networks.

-   The
[R](http://www.r-project.org/) software package
[[glmc]](http://cran.r-project.org/web/packages/glmc): Fitting
Generalized Linear Models Subject to Constraints.

-   The [R](http://www.r-project.org/) software package
[[RDS]](http://cran.r-project.org/web/packages/RDS): Provides
functionality for carrying out estimation with data collected using
Respondent-Driven Sampling.

-   The [R](http://www.r-project.org/) software package
[[sspse]](http://cran.r-project.org/web/packages/sspse):
Estimating Hidden Population Size using Respondent Driven Sampling Data.

-   The [R](http://www.r-project.org/) software package
[[network]](http://cran.r-project.org/web/packages/network):
Classes for Relational Data (Carter T. Butts, maintainer).

-   The [R](http://www.r-project.org/) software package
[[ergm.userterms]](http://cran.r-project.org/web/packages/ergm.userterms):
User-specified terms for the statnet suite of packages.

-   The [R](http://www.r-project.org/) software package
[[degreenet]](http://cran.r-project.org/web/packages/degreenet):
Models for Skewed Count Distributions Relevant to Networks.

- The paper:
[A Framework for the Comparison of Maximum Pseudo Likelihood and Maximum Likelihood Estimation of Exponential Family Random Graph
Models](https://doi.org/10.1016/j.socnet.2008.10.003)
by Marijtje A. van Duijn, Krista J. Gile, Mark S. Handcock in *Social Networks*, Volume 31, Issue 1, 2009, Pages 52-62
presents methodology to enable estimators of Exponential Family Random Graph model parameters to be compared.  
<br>
We use this methodology to compare
the bias, standard errors, coverage rates and efficiency of maximum likelihood and maximum pseudolikelihood estimators. We also propose an
improved pseudo-likelihood estimation method aimed at reducing bias. The comparison is performed using simulated social network data based on
two versions of an empirically realistic network model, the first representing Lazega's law firm data and the second a modified version with
increased transitivity. The framework considers estimation of both the natural and the mean-value parameters.
<br>
The software to reproduce the results in this paper are [here](https://github.com/handcock/ERGM_MPLE_MLE).

- I have developed statistical models and tools for tracking all-cause mortality and estimating excess mortality. This is to support the COVID-19 pandemic response. These tools are being used by the World Health Organization (WHO). The software has two components: a graphical user interface to the underlying statistical techniques, and the techniques themselves.  
<br>
Here is the resulting [WHO all cause of mortality and excess death calculator](https://worldhealthorg.shinyapps.io/WPRO-all-cause-of-mortality-and-excess-death-calculator/).  
<br>
Using the [Shiny](http://shiny.rstudio.com/) framework, I built an application that runs in a web browser and gives the user access to powerful visualization, analysis and modeling of All Cause mortality and Excess Death statistics, without requiring software installation or knowledge of programming in [R](http://www.r-project.org/).  
<br>
The software is open-source and does not require an internet connection to use. Details are on the [github site](https://github.com/handcock/WPROACM). Details of the statistical methodology are available [here](https://github.com/handcock/WPROACM/wiki/Methodology-used-in-WPROACM) and in the associated [publication](https://handcock.github.io/publication/who-acm-calc/).  
