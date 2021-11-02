---
title: "bssm: Bayesian Inference of Non-linear and Non-Gaussian State Space Models in R"
date: "2021-11-02"
author: "Jouni Helske and Matti Vihola"
publication_types : 
 - '2'
categories: 
  - Bayesian Inference
  - R Package
tags:
  - Markov Chain Monte Carlo
  - Sequential Monte Carlo
doi: ~
publishDate: '2021'
publication: "Accepted to R Journal"
publication_short: RJournal
featured: yes
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: "https://arxiv.org/abs/2101.08492"
url_video: ~
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
slides: ''
links:
  - icon: file-pdf
    icon_pack: fas
    name: PDF
    url: "https://arxiv.org/pdf/2101.08492"
    
---

## Abstract

We present an R package bssm for Bayesian non-linear/non-Gaussian state space modelling. Unlike the existing packages, bssm allows for easy-to-use approximate inference for the latent states based on Gaussian approximations such as the Laplace approximation and the extended Kalman filter. The package accommodates also discretised diffusion latent state processes. The inference is based on fully automatic, adaptive Markov chain Monte Carlo (MCMC) on the hyperparameters, with optional importance sampling post-correction to eliminate any approximation bias. The package implements also a direct pseudo-marginal MCMC or a delayed acceptance pseudo-marginal MCMC using the approximations. The package supports directly models with linear-Gaussian state dynamics (but with non-Gaussian observation models), and has an Rcpp interface for specifying custom non-linear models.
