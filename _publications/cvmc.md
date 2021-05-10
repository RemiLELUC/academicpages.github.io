---
title: "Control Variate Selection for Monte Carlo Integration"
collection: publications
permalink: /publication/control_variate
excerpt: "To appear in _Statistics and Computing_. With F.Portier and J.Segers. [PDF](https://arxiv.org/pdf/1906.10920),[code](https://github.com/RemiLELUC/ControlVariateSelection) 
# date: '2019-11-19'
# authors: "R.Leluc, F.Portier, J.Segers"
---
<p align="justify">
Monte Carlo integration with variance reduction by means of control variates can be implemented by the ordinary least squares estimator for the intercept in a multiple linear regression model with the integrand as response and the control variates as covariates. Even without special knowledge on the integrand, significant efficiency gains can be obtained if the control variate space is sufficiently large. Incorporating a large number of control variates in the ordinary least squares procedure may however result in (i) a certain instability of the ordinary least squares estimator and (ii) a possibly prohibitive computation time. Regularizing the ordinary least squares estimator by preselecting appropriate control variates via the Lasso turns out to increase the accuracy without additional computational cost. The findings in the numerical experiment are confirmed by concentration inequalities for the integration error.
