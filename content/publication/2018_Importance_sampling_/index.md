---
title: "Importance sampling type estimators based on approximate marginal Markov chain Monte Carlo"
date: "2020-09-03"
author: "Matti Vihola, Jouni Helske and Jordan Franks"
publication_types : 
 - '2'
categories:
 - Bayesian Inference
tags:
  - Markov Chain Monte Carlo
  - Sequential Monte Carlo
doi: ~
publishDate: '2020'
publication: "Scandinavian Journal of Statistics"
publication_short: ~
featured: no
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: "https://onlinelibrary.wiley.com/doi/10.1111/sjos.12492"
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
    url: "https://arxiv.org/pdf/1609.02541v6"
---

## Abstract

We consider importance sampling (IS) type weighted estimators based on Markov chain Monte Carlo (MCMC) targeting an approximate marginal of the target distribution. In the context of Bayesian latent variable models, the MCMC typically operates on the hyper parameters, and the subsequent weighting may be based on IS or sequential Monte Carlo (SMC), but allows for multilevel techniques as well. The IS approach provides a natural alternative to delayed acceptance (DA) pseudo-marginal/particle MCMC, and has many advantages over DA, including a straightforward parallelisation and additional flexibility in MCMC implementation. We detail minimal conditions which ensure strong consistency of the suggested estimators, and provide central limit theorems with expressions for asymptotic variances. We demonstrate how our method can make use of SMC in the state space models context, using Laplace approximations and time-discretised diffusions. Our experimental results are promising and show that the IS type approach can provide substantial gains relative to an analogous DA scheme, and is often competitive even without parallelisation.
