---
title: "Introducing libeemd: A program package for performing the ensemble empirical mode decomposition"
date: "2016-01-01"
author: "Perttu J.J. Luukko and Jouni Helske and Esa Räsänen"
publication_types : 
 - '2'
categories: 
  - R package
tags:
  - Empirical mode decomposition
doi: ~
publishDate: '2016'
publication: 'Computational Statistics'
publication_short: ~
featured: no
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: https://link.springer.com/article/10.1007/s00180-015-0603-9
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
    url: "https://jyx.jyu.fi/bitstream/handle/123456789/49577/luukkohelskerasanenintroducinglibeemaprogrampackafeforperforming.pdf"
---

## Abstract

The ensemble empirical mode decomposition (EEMD) and its complete variant (CEEMDAN) are adaptive, noise-assisted data analysis methods that improve on the ordinary empirical mode decomposition (EMD). All these methods decompose possibly nonlinear and/or nonstationary time series data into a finite amount of components separated by instantaneous frequencies. This decomposition provides a powerful method to look into the different processes behind a given time series data, and provides a way to separate short time-scale events from a general trend. We present a free software implementation of EMD, EEMD and CEEMDAN and give an overview of the EMD methodology and the algorithms used in the decomposition. We release our implementation, libeemd, with the aim of providing a user-friendly, fast, stable, well-documented and easily extensible EEMD library for anyone interested in using (E)EMD in the analysis of time series data. While written in C for numerical efficiency, our implementation includes interfaces to the Python and R languages, and interfaces to other languages are straightforward. 