---
title: "Accurate non-stationary short-term traffic flow prediction method"
authors:
- admin
date: "2022-05-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Precise and timely traffic flow prediction plays a critical role in developing intelligent transportation systems and has attracted considerable attention in recent decades. Despite the significant progress in this area brought by deep learning, challenges remain. Traffic flows usually change dramatically in a short period, which prevents the current methods from accurately capturing the future trend and likely causes the over-fitting problem, leading to unsatisfied accuracy. To this end, this paper proposes a Long Short-Term Memory (LSTM) based method that can forecast the short-term traffic flow precisely and avoid local optimum problems during training. Specifically, instead of using the non-stationary raw traffic data directly, we first decompose them into sub-components, where each one is less noisy than the original input. Afterward, Sample Entropy (SE) is employed to merge similar components to reduce the computation cost. The merged features are fed into the LSTM, and we then introduce a spatiotemporal module to consider the neighboring relationships in the recombined signals to avoid strong autocorrelation. During training, we utilize the Grey Wolf Algorithm (GWO) to optimize the parameters of LSTM, which overcome the overfitting issue. We conduct the experiments on a UK public highway traffic flow dataset, and the results show that the proposed method performs favorably against other state-of-the-art methods with better adaption performance on extreme outliers, delay effects, and trend-changing responses.

# Summary. An optional shortened abstract.
summary: This paper proposes a method for accurate short-term traffic flow prediction.

tags:
- Deep Learning

featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2205.00517
url_pdf: https://arxiv.org/abs/2205.00517
url_code: 'https://github.com/Bobbed1999'
#url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "top"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on Prediction of interval traffic flow.

