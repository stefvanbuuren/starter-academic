---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Multiple imputation in data that grow over time: A comparison of three strategies'
subtitle: ''
summary: ''
authors:
- XM Kavelaars
- S Van Buuren
- JR Van Ginkel
tags:
- '""'
categories: []
date: '2019-01-01'
lastmod: 2020-11-09T20:53:52+01:00
featured: false
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
publishDate: '2020-11-09T19:53:52.020275Z'
publication_types:
- '2'
abstract: Multiple imputation is a highly recommended technique to deal with missing
  data, but the application to longitudinal datasets can be done in multiple ways.
  When a new wave of longitudinal data arrives, we can treat the combined data of
  multiple waves as a new missing data problem and overwrite existing imputations
  with new values (re-imputation). Alternatively, we may keep the existing imputations,
  and impute only the new data. We may do either a full multiple imputation (nested)
  or a single imputation (appended) on the new data per imputed set. This study compares
  these three strategies by means of simulation. All techniques resulted in valid
  inference under a monotone missingness pattern. A non-monotone missingness pattern
  led to biased and non-confidence valid regression coefficients after nested and
  appended imputation, depending on the correlation structure of the data. Correlations
  within timepoints must be stronger than correlations between timepoints to obtain
  valid inference. In an empirical example, the three strategies performed similarly.
  We conclude that appended imputation is especially beneficial in longitudinal datasets
  that suffer from dropout.
publication: '*arXiv preprint arXiv:1904.04185*'
---
