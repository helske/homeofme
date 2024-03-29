---
title: "seqHMM: Mixture Hidden Markov Models for Social Sequence Data and Other Multivariate, Multichannel Categorical Time Series"
date: "2021-04-01"
author: "Jouni Helske and Satu Helske"
categories: 
  - R Package
  - Hidden Markov Models
tags: ~
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
  url: https://github.com/helske/seqHMM
- icon: file-pdf
  icon_pack: fas
  name: PDF for the paper
  url: "https://www.jstatsoft.org/index.php/jss/article/view/v088i03/v88i03.pdf"
---

Designed for fitting hidden (latent) Markov models and mixture hidden Markov models for social sequence data and other categorical time series. Also some more restricted versions of these type of models are available: Markov models, mixture Markov models, and latent class models. The package supports models for one or multiple subjects with one or multiple parallel sequences (channels). External covariates can be added to explain cluster membership in mixture models. The package provides functions for evaluating and comparing models, as well as functions for visualizing of multichannel sequence data and hidden Markov models. Models are estimated using maximum likelihood via the EM algorithm and/or direct numerical maximization with analytical gradients. All main algorithms are written in C++ with support for parallel computation. Documentation is available via several vignettes in this page, and the paper by Helske and Helske (2019, <doi:10.18637/jss.v088.i03>).
