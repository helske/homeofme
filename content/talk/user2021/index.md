---
author: Jouni Helske
categories:
  - Bayesian Inference
  - R package
date: "2021-07-09"
date_end: "2021-07-09"
draft: false
event: UseR!2021 conference
event_url: https://user2021.r-project.org/
excerpt: State space models are a flexible class of latent variable models commonly used in analysing time series data. The R package bssm is designed for Bayesian inference of general state space models with non-Gaussian and/or non-linear observational and state equations. The package provides easy-to-use and efficient functions for fully Bayesian inference with common time series models such as basic structural time series model with exogenous covariates, simple stochastic volatility models, and discretized diffusion models, making it straightforward and efficient to make predictions and other inference in a Bayesian setting. Unlike the existing packages, bssm allows for easy-to-use approximate inference based on Gaussian approximations such as the Laplace approximation and the extended Kalman filter. The inference is based on fully automatic, adaptive Markov chain Monte Carlo (MCMC) on the hyperparameters, with optional parallelizable importance sampling post-correction to eliminate any approximation bias. The bssm package implements also a direct pseudo-marginal MCMC and a delayed acceptance pseudo-marginal MCMC using intermediate approximations. The package supports directly models with linear-Gaussian state dynamics with non-Gaussian observation models and has an Rcpp interface for specifying custom non-linear and diffusion models.
featured: true
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: Slides
  url: /files/bssm/bssm-helske-user2021.html
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/helske/bssm
location: Session 9C, online UseR!2021 Conference
show_post_time: false
subtitle: ~
title: "bssm: Bayesian Inference of Non-linear and Non-Gaussian State Space Models in R"
---

