---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dual imputation model for incomplete longitudinal data.
subtitle: ''
summary: ''
authors:
- S Jolani
- LE Frank
- admin
tags:
- '""'
categories: []
date: '2014-01-01'
lastmod: 2020-11-06T09:12:10+01:00
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
publishDate: '2020-11-06T08:12:10.126856Z'
publication_types:
- '2'
abstract: Missing values are a practical issue in the analysis of longitudinal data.
  Multiple imputation (MI) is a well-known likelihood-based method that has optimal
  properties in terms of efficiency and consistency if the imputation model is correctly
  specified. Doubly robust (DR) weighing-based methods protect against misspecification
  bias if one of the models, but not necessarily both, for the data or the mechanism
  leading to missing data is correct. We propose a new imputation method that captures
  the simplicity of MI and protection from the DR method. This method integrates MI
  and DR to protect against misspecification of the imputation model under a missing
  at random assumption. Our method avoids analytical complications of missing data
  particularly in multivariate settings, and is easy to implement in standard statistical
  packages. Moreover, the proposed method works very well with an intermittent pattern
  of missingness when other DR methods can not be used. Simulation experiments show
  that the proposed approach achieves improved performance when one of the models
  is correct. The method is applied to data from the fireworks disaster study, a randomized
  clinical trial comparing therapies in disaster-exposed children. We conclude that
  the new method increases the robustness of imputations.
publication: '*Br J Math Stat Psychol*'
url_pdf: 'publications/2013 Dual imputation - BJMSP.pdf'
---
