---
title: "tsPI: Improved Prediction Intervals for ARIMA Processes and Structural Time Series"
date: "2020-06-01"
author: "Jouni Helske"
categories: 
  - R Package
  - State Space Models
tags:
  - KFAS
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/helske/tspI
- icon: file-pdf
  icon_pack: fas
  name: PDF for the paper
  url: "https://www.univaasa.fi/materiaali/pdf/isbn_978-952-476-523-7.pdf"
---

Prediction intervals for ARIMA and structural time series models using importance sampling approach with uninformative priors for model parameters, leading to more accurate coverage probabilities in frequentist sense. Instead of sampling the future observations and hidden states of the state space representation of the model, only model parameters are sampled, and the method is based solving the equations corresponding to the conditional coverage probability of the prediction intervals. This makes method relatively fast compared to for example MCMC methods, and standard errors of prediction limits can also be computed straightforwardly.