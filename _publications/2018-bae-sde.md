---
title: "Calibration of simplified building energy models for parameter estimation
and forecasting: stochastic versus deterministic modelling"
collection: publications
permalink: /publication/2018-bae-sde
excerpt: 'This paper investigates how accounting for modelling errors affects the results of model calibration.'
date: 2018-04-15
venue: 'Building and Environment'
---

Rouchier S, Rabouille M, Oberlé P (2018) Calibration of simplified building energy models for paramater estimation and forecasting: stochastic versus deterministic modelling, *Building and Environment*, vol. 134, p.181-190

[Download paper here](http://srouchier.github.io/files/2018-bae-sde.pdf)

Due to the ill-posedness of many inverse problems, parameter estimates are often prone to a possibly large uncertainty, caused by a series of errors and approximations in the experimental and modelling work. Stochastic state-space models for time series modelling incorporate a term of process noise that represents system error; most studies on building thermal model calibration however employ deterministic models that overlook this error.

This paper investigates how accounting for modelling errors affects the results of model calibration. Several simplified models are defined to simulate the indoor temperature of an experimental test cell. Some models include process noise and others do not. The parameters of each model are then learned repeatedly by using
several training datasets from the test cell. The MCMC algorithm is used for training. The robustness of parameter estimates between independent trainings is evaluated. Then, the forecasting ability of the deterministic and stochastic options are compared, in terms of accuracy and robustness. Results show that stochastic modelling considerably increases the uncertainty of parameter estimates, but ensures their consistency between separate trainings, whereas deterministic models are less robust and offer a less reliable forecasting.
