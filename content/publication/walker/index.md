---
title: "Efficient Bayesian generalized linear models with time-varying coefficients: The walker package in R"
date: "2022-02-13"
author: "Jouni Helske"
publication_types : 
 - '2'
categories: 
  - Bayesian Inference
  - R Package
tags:
  - Markov Chain Monte Carlo
  - Time Series
doi: ~
publishDate: '2022'
publication: "SoftwareX"
publication_short: SoftwareX
featured: yes
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: "https://www.sciencedirect.com/science/article/pii/S235271102200022X"
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
    url: "https://www.sciencedirect.com/science/article/pii/S235271102200022X/pdfft?md5=fbead3e873ba642f75363ff42e3046dc&pid=1-s2.0-S235271102200022X-main.pdf"
    
---

## Abstract

The R package walker extends standard Bayesian general linear models to the case where the effects of the explanatory variables can vary in time. This allows, for example, to model the effects of interventions such as changes in tax policy which gradually increases their effect over time. The Markov chain Monte Carlo algorithms powering the Bayesian inference are based on Hamiltonian Monte Carlo provided by Stan software, using a state space representation of the model to marginalise over the regression coefficients for efficient low-dimensional sampling.

