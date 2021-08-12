---
title: "Mixture Hidden Markov Models for Sequence Data: The seqHMM Package in R"
date: "2019-01-01"
author: "Satu Helske and Jouni Helske"
publication_types : 
 - '2'
categories:
  - Hidden Markov Models
  - R package
tags: ~
doi: https://doi.org/10.18637/jss.v088.i03
publishDate: '2019'
publication: "Journal of Statistical Software"
publication_short: ~
featured: no
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: "https://www.jstatsoft.org/v088/i03"
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
    url: "https://www.jstatsoft.org/index.php/jss/article/view/v088i03/v88i03.pdf"
---

## Abstract

Sequence analysis is being more and more widely used for the analysis of social sequences and other multivariate categorical time series data. However, it is often complex to describe, visualize, and compare large sequence data, especially when there are multiple parallel sequences per subject. Hidden (latent) Markov models (HMMs) are able to detect underlying latent structures and they can be used in various longitudinal settings: to account for measurement error, to detect unobservable states, or to compress information across several types of observations. Extending to mixture hidden Markov models (MHMMs) allows clustering data into homogeneous subsets, with or without external covariates. The seqHMM package in R is designed for the efficient modeling of sequences and other categorical time series data containing one or multiple subjects with one or multiple interdependent sequences using HMMs and MHMMs. Also other restricted variants of the MHMM can be fitted, e.g., latent class models, Markov models, mixture Markov models, or even ordinary multinomial regression models with suitable parameterization of the HMM. Good graphical presentations of data and models are useful during the whole analysis process from the first glimpse at the data to model fitting and presentation of results. The package provides easy options for plotting parallel sequence data, and proposes visualizing HMMs as directed graphs.
