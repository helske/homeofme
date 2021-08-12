---
title: "Graphical model inference: Sequential Monte Carlo meets deterministic approximations"
date: "2018-01-01"
author: "Fredrik Lindsten, Jouni Helske and Matti Vihola"
publication_types : 
 - '6'
categories: ~
tags:
  - Sequential Monte Carlo
doi: ~
publishDate: '2018'
publication: "Advances in Neural Information Processing Systems 31"
publication_short: ~
featured: no
url_pdf: ~
url_code: ~
url_dataset: ~
url_poster: ~
url_project: ~
url_slides: ~
url_source: "http://papers.nips.cc/paper/8041-graphical-model-inference-sequential-monte-carlo-meets-deterministic-approximations.pdf"
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
    url: "http://papers.nips.cc/paper/8041-graphical-model-inference-sequential-monte-carlo-meets-deterministic-approximations.pdf"
---

## Abstract

Approximate inference in probabilistic graphical models (PGMs) can be grouped into deterministic methods and Monte-Carlo-based methods. The former can often provide accurate and rapid inferences, but are typically associated with biases that are hard to quantify. The latter enjoy asymptotic consistency, but can suffer from high computational costs. In this paper we present a way of bridging the gap between deterministic and stochastic inference. Specifically, we suggest an efficient sequential Monte Carlo (SMC) algorithm for PGMs which can leverage the output from deterministic inference methods. While generally applicable, we show explicitly how this can be done with loopy belief propagation, expectation propagation, and Laplace approximations. The resulting algorithm can be viewed as a post-correction of the biases associated with these methods and, indeed, numerical results show clear improvements over the baseline deterministic methods as well as over plain SMC.
