---
title: "Interval Short-Term Traffic Flow Prediction Method Based on CEEMDAN-SE Nosie Reduction and LSTM Optimized by GWO"
authors:
- admin
- Yuer Yang
- Zihao Lu

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-08-10T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Wireless Communications and Mobile Computing, 2022*(1)"
publication_short: ""


abstract: With rapid economic growth and urbanization, the accelerated increase in car ownership has brought massive pressure on urban traffic, and accurate traffic flow prediction information can provide an important basis for urban traffic dynamic planning. The existing methods have problems such as low efficiency, large error, and inability to adapt to short-term traffic changes. To solve the above problems, the CEEMDAN-SE-GWO-LSTM method was proposed in this paper. First, the traffic flow data is processed for outliers and missing values. The Complete ensemble empirical mode decomposition with adaptive noise (CEEMDAN) method is used to decompose the traffic flow data, and sample entropy (SE) is used to reconstruct the subsequence, which is used to improve the quality of the input data. Then, the Grey Wolf Optimizer (GWO) is used to optimize the parameters of the long-short-term memory (LSTM) in order to improve the prediction accuracy and prevent the model from falling into a local optimum. Three models are used to compare with the ensemble model proposed in this paper, including back propagation neural network (BPNN), LSTM, and long-short-term memory optimized by Grey Wolf Optimizer (GWO-LSTM). Root mean square error (RMSE) is reduced by 40.9% to 66.7%; R2 score is improved by 1.5% to 7.1%. The experimental results show that CEEMDAN-SE-GWO-LSTM has a higher prediction accuracy than the existing traffic flow prediction models. Finally, this paper uses the model prediction error to establish an interval prediction model based on the kernel density estimation theory, which enhances the generalization of the model and the practical application value.

# Summary. An optional shortened abstract.
summary: A Robust Method for Short-Term Traffic Flow Prediction.

tags:
- Source Themes
featured: false

# this is for show preprint button?
# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
  # - type: pdf
  #   url: http://arxiv.org/pdf/1512.04133v1
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  - type: source
    url: "https://onlinelibrary.wiley.com/doi/full/10.1155/2022/5257353"
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- > [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
