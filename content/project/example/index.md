---
title: Hyperspectral Image (HSI) Classification
summary: Graduation project with thesis.
tags:
  - SVM
date: '2022-05-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Indian Pines ground truth
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Hyperspectral image (HSI) classification is widely used in remote sensing image analysis. Typically, supervised or unsupervised methods are employed to introduce spatial information, combining the spectral and spatial information of remote sensing images, which has become an effective means to achieve good classification results.

In this paper, a simple supervised method is used to introduce spatial coordinates as spatial information, and three HSI classification algorithms are implemented, where the spatial coordinates of the samples are considered as spatial features. One of the implemented methods is a spectral-spatial feature fusion HSI classification algorithm based on spatial coordinates. The remote sensing image dataset is randomly divided in the spatial dimension, and 10% of the samples are selected as training samples. Support Vector Machines (SVM) are used to classify the samples, obtaining the probability that each sample belongs to each classification category based on both spectral features and spatial coordinate features. SVM is further used to classify the probability features to obtain the final classification result.

Experimental results show that spatial coordinates are useful spatial information, and the spectral-spatial feature fusion classification algorithm (SSFFSC) effectively improves classification accuracy by using spatial coordinates as spatial features.
