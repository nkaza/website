---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Smart Meters Data for Modeling and Forecasting Water Demand at the User-level
subtitle: ''
summary: ''
authors:
- J. E Pesantez
- E. Z. Berglund
- N. Kaza
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-02-18T11:49:56-05:00
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
publishDate: '2021-02-18T16:49:56.536845Z'
publication_types:
- '2'
abstract: ' Smart meters installed at the user-level provides a new data source for
  managing water infrastructure. This research explores the use of machine learning
  methods to forecast hourly water demand using smart meter data at the user-level.
  Random Forests (RF), Artificial Neural Network (ANN), and Support Vector Regression
  (SVR) are applied to forecast demand using predictors that include lagged demand,
  seasonality, weather, and household characteristics. Time-series clustering is applied
  to differentiate the time of day and days of the week, which improves model performance.
  Two modeling approaches are compared. Individual models are developed separately
  for each smart meter, and a group model is trained using a dataset of multiple meters.
  The approaches perform similarly well. Individual models predict demands at specific
  meters with lower error, while the group model predicts demands at new meters with
  lower error. Results demonstrate that RF and ANN perform better than SVR across
  all scenarios.'
publication: '*Environmental Modelling and Software*'
doi: https://doi.org/10.1016/j.envsoft.2020.104633
url_pdf: '/files/pdfs/enso104633.pdf'
---