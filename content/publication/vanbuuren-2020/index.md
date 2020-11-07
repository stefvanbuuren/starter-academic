---
title: Broken stick model for irregular longitudinal data
subtitle: ''
summary: ''
authors:
- admin
tags:
- brokenstick
- R
- linear mixed model
- repeated measures
- linear B-spline
- personalised estimation
- growth curve analysis
- critical periods
- time-to-time correlation
- profile analysis
- curve interpolation
- multiple imputation
- curve matching
- two-step method
categories: []
date: '2020-01-01'
lastmod: 2020-11-06T16:46:45+01:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-11-06T15:46:45.141067Z'
publication_types:
- '2'
abstract: 'Many longitudinal studies collect data that have irregular observation
  times, often requiring the application of linear mixed models with time-varying
  outcomes. This paper presents an alternative that splits the quantitative analysis
  into two steps. The first step converts irregularly observed data into a set of
  repeated measures through the broken stick model. The second step estimates the
  parameters of scientific interest from the repeated measurements at the subject
  level. The broken stick model approximates each subject’s trajectory by a series
  of connected straight lines. The breakpoints, specified by the user, divide the
  time axis into consecutive intervals common to all subjects. We restrict the methodology
  to just three variables: time, measurement and subject. The model is a special case
  of the linear mixed model, with time as a linear B-spline and with subject as the
  grouping factor. The main assumptions are: Subjects are exchangeable, trajectories
  between two breakpoints are all straight, random effects follow a multivariate normal
  distribution, and unobserved data are missing at random (MAR). The pkgbrokenstick
  R package offers tools to calculate, predict, impute and visualise broken stick
  estimates. The package supports two optimisation methods, including options to constrain
  the variance-covariance matrix of the random effects. We demonstrate a few applications
  of the model: detection of critical periods, estimation of the time-to-time correlations,
  profile analysis, curve interpolation, multiple imputation and personalised prediction
  of future outcomes by curve matching.'
publication: '*Journal of Statistcal Software*'
url_preprint: ./publications/2020_Brokenstick_JSS_manuscript.pdf
links:
  - icon_pack: fa
    icon: book
    name: Manual
    url: 'https://growthcharts.org/brokenstick/'
  - icon_pack: fab
    icon: github
    name: Source
    url: 'https://github.com/growthcharts/brokenstick'
---
