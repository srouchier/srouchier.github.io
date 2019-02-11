---
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /software.html
---

This page is a list of a few software resources I either developed, or contributed to developing: Jupyter notebooks, Python libraries, and other tutorials.

# InverseBuilding: solving inverse problems in building physics

[InverseBuilding](https://srouchier.github.io/InverseBuilding/) is a series of courses showing how to solve various types of inverse problems, or model calibration problems, in building physics applications. Examples of tutorials include:

* [Estimating the heat conductivity](https://nbviewer.jupyter.org/github/srouchier/InverseBuilding/blob/master/01_HeatConductivity/Notebook_HeatConductivity.ipynb) of a wall with Bayesian inference

<img src="/images/software-inverse-1.png" style="width: 450px;">

* [Calculating a boundary heat flow](https://nbviewer.jupyter.org/github/srouchier/InverseBuilding/blob/master/02_HeatFlow/Notebook_HeatFlow.ipynb) from temperature measurements by solving the linear and transient inverse heat conduction problem

<img src="/images/software-inverse-2.png" style="width: 350px;">

# hamopy: heat, air and moisture transfer in python

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
