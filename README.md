# CensMixReg
Censored Linear Mixture Regression Models - CensMixReg is a R library to fit censored linear regression models where the random errors follow a finite mixture of Scale Mixture Normal distributions. Fit censored linear models of finite mixture multivariate Student-t and Normal distributions. Fit censored mixture regression models based on scale mixture of normal distributions. Specifically, this repository contains the code for the paper 
[Finite mixture modeling of censored data using the multivariate Student-t distribution](https://www.sciencedirect.com/science/article/pii/S0047259X1730310X)
Published at JMVA 2017.

## Abstract:
Finite mixture models have been widely used for the modeling and analysis of data
from a heterogeneous population. Moreover, data of this kind can be subject to some
upper and/or lower detection limits because of the restriction of experimental apparatus.
Another complication arises when measures of each population depart significantly from
normality, for instance, in the presence of heavy tails or atypical observations. For such
data structures, we propose a robust model for censored data based on finite mixtures
of multivariate Student-t distributions. This approach allows us to model data with great
flexibility, accommodating multimodality, heavy tails and also skewness depending on the
structure of the mixture components. We develop an analytically simple, yet efficient,
EM-type algorithm for conducting maximum likelihood estimation of the parameters.
The algorithm has closed-form expressions at the E-step that rely on formulas for the
mean and variance of the multivariate truncated Student-t distributions. Further, a general
information-based method for approximating the asymptotic covariance matrix of the
estimators is also presented. Results obtained from the analysis of both simulated and real
datasets are reported to demonstrate the effectiveness of the proposed methodology. The
proposed algorithm and methods are implemented in the new R package CensMixReg.

## Authors
The library is developed by [Luis Benites Sanchez](https://github.com/lbenitesanchez), [Víctor Hugo Lachos](https://hlachos.stat.uconn.edu/) and [Edgar Javier López](https://github.com/ejlopezmor). 
