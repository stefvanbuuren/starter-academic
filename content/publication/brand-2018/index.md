---
title: Combining multiple imputation and bootstrap in the analysis of cost-effectiveness
  trial data
subtitle: ''
summary: ''
authors:
- J. P. L. Brand
- admin
- S. le Cessie
- W. B. van den Hout
tags: 
- multiple imputation
- bootstrap
- cost-effectiveness
categories: []
date: '2019-01-30'
lastmod: 2020-11-09T20:55:32+01:00
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
publishDate: '2020-11-09T19:55:32.560782Z'
publication_types:
- '2'
abstract: 'In healthcare cost-effectiveness analysis, probability distributions are typically skewed and missing data are frequent. Bootstrap and multiple imputation are well-established resampling methods for handling skewed and missing data. However, it is not clear how these techniques should be combined. This paper addresses combining multiple imputation and bootstrap to obtain confidence intervals of the mean difference in outcome for two independent treatment groups. We assessed statistical validity and efficiency of 10 candidate methods and applied these methods to a clinical data set. Single imputation nested in the bootstrap percentile method (with added noise to reflect the uncertainty of the imputation) emerged as the method with the best statistical properties. However, this method can require extensive computation times and the lack of standard software makes this method not accessible for a larger group of researchers. Using a standard unpaired t-test with standard multiple imputation without bootstrap appears to be a robust alternative with acceptable statistical performance for which standard multiple imputation software is available.'
publication: '*Statistics in Medicine*'
url_pdf: publications/2019_mi_bootstrap.pdf
---
