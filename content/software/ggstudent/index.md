---
title: "ggstudent: Continuous Confidence Interval Plots using t-Distribution"
date: "2020-07-01"
author: "Jouni Helske"
categories: 
  - R Package
  - Visualization
tags: ~
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
  url: https://github.com/helske/ggstudent
---

Provides an extension to 'ggplot2' (Wickham, 2016, <doi:10.1007/978-3-319-24277-4>) for creating two types of continuous confidence interval plots (Violin CI and Gradient CI plots), typically for the sample mean. These plots contain multiple user-defined confidence areas with varying colours, defined by the underlying t-distribution used to compute standard confidence intervals for the mean of the normal distribution when the variance is unknown. Two types of plots are available, a gradient plot with rectangular areas, and a violin plot where the shape (horizontal width) is defined by the probability density function of the t-distribution.