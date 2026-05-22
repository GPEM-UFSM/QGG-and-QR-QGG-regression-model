# NGGD Distribution and Regression Model

This repository contains the supplementary materials, R codes, Monte Carlo simulation scripts, real-data applications, and Shiny application developed for the **New Generalized Gompertz Distribution (NGGD)** and its associated regression model.

The NGGD distribution is proposed as a flexible model for positive continuous data. Its regression structure allows the distributional parameters to be modeled as functions of explanatory variables, making it suitable for applications involving asymmetric, skewed, or non-normal positive responses.

The materials available in this repository support the reproducibility of the simulation study, model fitting procedures, graphical analyses, diagnostic tools, and applied examples presented in the associated paper.

## Repository Contents

This repository includes:

- R functions for the NGGD distribution;
- scripts for parameter estimation by maximum likelihood;
- Monte Carlo simulation codes;
- real-data application scripts;
- supplementary material related to the simulation study;
- diagnostic and graphical analysis routines;
- a Shiny application for interactive visualization of the NGGD distribution, skewness coefficient, and kurtosis coefficient.

## Main Features

The implemented materials allow users to:

- evaluate the probability density function of the NGGD distribution;
- compute the cumulative distribution function;
- obtain quantiles;
- generate random values;
- estimate model parameters by maximum likelihood;
- reproduce Monte Carlo simulation studies;
- fit the associated NGGD regression model;
- compare fitted models using goodness-of-fit measures and information criteria;
- perform graphical and residual diagnostic analyses;
- explore the behavior of the distribution, skewness coefficient, and kurtosis coefficient through a Shiny interface.

## Shiny Application

The repository contains a Shiny application developed to interactively explore the behavior of the NGGD distribution.

The app allows users to visualize how changes in the model parameters affect the shape of the probability density function and the overall distributional behavior of the model. In addition, the application provides graphical tools for analyzing the skewness and kurtosis coefficients, making it possible to investigate the flexibility of the NGGD distribution under different parameter settings.

To run the Shiny app in R, use:

```r
[Access the Shiny app](https://gfem-ufsm.github.io/NGGD-and-NGG-regression-model/)
