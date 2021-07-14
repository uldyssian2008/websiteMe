---
abstract: Optimal transport (OT) is a widely used technique for distribution
  alignment, with applications throughout the machine learning, graphics, and
  vision communities. Without any additional structural assumptions
  on.                      transport, however, OT can be fragile to outliers or
  noise, especially in high dimensions. Here, we introduce Latent Optimal
  Transport (LOT), a new approach for OT that simultaneously learns
  low-dimensional structure in data while leveraging this structure to solve the
  alignment task. The idea behind our approach is to learn two sets of “anchors”
  that constrain the flow of transport between a source and target distribution.
  In both theoretical and empirical studies, we show that LOT regularizes the
  rank of transport and makes it more robust to outliers and the sampling
  density. We show that by allowing the source and target to have different
  anchors, and using LOT to align the latent spaces between anchors, the
  resulting transport plan has better structural interpretability and highlights
  connections between both the individual data points and the local geometry of
  the datasets.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Chi-Heng Lin
  - Mehdi Azabou
  - Eva L Dyer
author_notes: []
publication: ICML 2021
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Making transport more robust and interpretable by moving data through a
  small number of anchor points.
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2021-07-14T01:53:52.168Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).