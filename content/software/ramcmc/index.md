---
title: "ramcmc: Robust Adaptive Metropolis Algorithm"
date: "2020-06-01"
author: "Jouni Helske"
categories: 
  - R Package
tags: 
  - Markov Chain Monte Carlo
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
slides: ~
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/helske/ramcmc
---

Function for adapting the shape of the random walk Metropolis proposal as specified by robust adaptive Metropolis algorithm by Vihola (2012) <doi:10.1007/s11222-011-9269-5>. The package also includes fast functions for rank-one Cholesky update and downdate. These functions can be used directly from R or the corresponding C++ header files can be easily linked to other R packages.