---
title: 'Missing Data in Clinical Research: A Tutorial on Multiple Imputation'
date: '2021-01-01'
draft: true
publishDate: '2020-11-26T09:39:50.834258Z'
authors:
- Peter C. Austin
- Ian R. White
- Douglas S. Lee
- admin
publication_types:
- '2'
abstract: Missing data is a common occurrence in clinical research. Missing data occurs
  when the value of the variables of interest are not measured or recorded for all
  subjects in the sample. Common approaches to addressing the presence of missing
  data include complete-case analyses, in which subjects with missing data are excluded,
  or mean-value imputation, where missing values are replaced with the mean value
  of that variable in those subjects for whom it is not missing. However, in many
  settings, these approaches can lead to biased estimates of statistics (e.g., of
  regression coefficients) and/or to confidence intervals that are artificially narrow.
  Multiple imputation (MI) is a popular approach for addressing the presence of missing
  data. With MI, multiple plausible values of a given variable are imputed or filled-in
  for each subject who has missing data for that variable. This results in the creation
  of multiple completed datasets. Identical statistical analyses are conducted in
  each of these complete datasets and the results are pooled across complete datasets.
  We provide an introduction to MI and discuss issues in its implementation, including
  developing the imputation model, how many imputed datasets to create, and addressing
  derived variables. We illustrate the application of MI through an analysis of data
  on patients hospitalized with heart failure. We focus on developing a model to estimate
  the probability of one-year mortality in the presence of missing data. Statistical
  software code for conducting multiple imputation in R, SAS, and Stata are provided.
featured: false
publication: '*Canadian Journal of Cardiology*'
tags:
- '""'
---

