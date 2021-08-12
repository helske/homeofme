---
title: "walker: Bayesian Generalized Linear Models with Time-Varying Coefficients"
date: "2021-06-01"
author: "Jouni Helske"
categories: 
  - R Package
  - State Space Models
  - Bayesian Inference
tags: ~
featured: yes
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/helske/walker
- icon: file-pdf
  icon_pack: fas
  name: PDF for the paper
  url: "https://arxiv.org/pdf/2009.07063"
---

Bayesian generalized linear models with time-varying coefficients as in Helske (2020, <arXiv:2009.07063>). Gaussian, Poisson, and binomial observations are supported. The Markov chain Monte Carlo (MCMC) computations are done using Hamiltonian Monte Carlo provided by Stan, using a state space representation of the model in order to marginalise over the coefficients for efficient sampling. For non-Gaussian models, the package uses the importance sampling type estimators based on approximate marginal MCMC as in Vihola, Helske, Franks (2020, <doi:10.1111/sjos.12492>).