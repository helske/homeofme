---
title: "Rlibeemd: Ensemble Empirical Mode Decomposition (EEMD) and Its Complete Variant (CEEMDAN)"
date: "2020-06-05"
author: "Jouni Helske and Perttu Luukko"
categories: 
  - R Package
tags:
  - Empirical Mode Decomposition
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
  url: https://github.com/helske/rlibeemd
- icon: file-pdf
  icon_pack: fas
  name: PDF for the paper
  url: "https://link.springer.com/content/pdf/10.1007/s00180-015-0603-9.pdf"
---

An R interface for libeemd (Luukko, Helske, Räsänen, 2016) <doi:10.1007/s00180-015-0603-9>, a C library of highly efficient parallelizable functions for performing the ensemble empirical mode decomposition (EEMD), its complete variant (CEEMDAN), the regular empirical mode decomposition (EMD), and bivariate EMD (BEMD). Due to the possible portability issues CRAN version no longer supports OpenMP, you can install OpenMP-supported version from GitHub: <https://github.com/helske/Rlibeemd/>.
