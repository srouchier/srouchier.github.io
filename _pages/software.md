---
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /software.html
---

This page is a list of a few software resources I either developed, or contributed to developing: Jupyter notebooks, Python libraries, and other tutorials.

## pySIP: stochastic state-space inference and prediction in Python

Ordinary differential equations, determined from first-principles, can be used for modeling physical systems. However, the exact dynamics of such systems are uncertain and only measured at discrete-time instants through non-ideal sensors. In this case, stochastic differential equations provide a modeling framework which is more robust to these uncertainties. The stochastic part of the state-space model can accomodate for unmodeled disturbances, which do not have a significant influence on the system dynamics. Otherwise, unmeasured disturbances can be modeled as temporal Gaussian Processes with certain parametrized covariance structure. The resulting Latent Force Model is a combination of parametric grey-box model and non-parametric Gaussian process model.

[pySIP](https://github.com/locie/pySIP) provides a framework for infering continuous time linear stochastic state-space models. For that purpose, it is possible to chose between a frequentist and a Bayesian workflow. Each workflow allows to estimate the parameters, assess the inference and model reliability, and perform model selection.

<img src="https://buildingenergygeeks.org/images/data/ssm03_output.png" style="width: 350px;">

## hamopy: heat, air and moisture transfer in python

[Hamopy](https://srouchier.github.io/hamopy/) is a python package for the numerical simulation of one-dimensional heat, air and moisture (HAM) transfer in porous materials. Its principle is the finite-element resolution of the HAM conservation equations.

Hamopy makes good use of its open-source nature, and gives users complete control over the simulation process. One can:
* add new materials and customise the equations defining their properties,
* account for water flow and storage in both liquid and vapor states,
* include time-dependent boundary conditions,
* work with fully coupled hygrothermal transfer, or with thermal transfer only (saves time),
* easily automate many simulations for sensitivity analyses, evolutionary algorithms and such.

The library comes with a few examples:
* Hamstad BM3: third exercise of the Hamstad benchmark package
<img src="/images/software-hamopy-1.png" style="width: 400px;">
* Hamstad BM5: fifth exercise of the Hamstad benchmark package
<img src="/images/software-hamopy-2.png" style="width: 400px;">
