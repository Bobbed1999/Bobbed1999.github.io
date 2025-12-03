---
title: 'Causal Reinforcement Learning based Agent-Patient Interaction with Clinical Domain Knowledge'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Elene Kajaia
  - Ruth Lopez
  - Shu-Fen Wung
  - Kevin Berner
  - Fengpei Yuan


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *ICRA under review*"
publication_short: "In *ICRA*"

abstract: We introduce an embodied robotic implementation of the \textbf{PARTNER} framework (Personalized AI and Robotics to Nurture Engaging Reminiscence), a distributed multimodal architecture for emotion-aware, personalized dialogue in socially assistive contexts. The framework has three components: a secure cloud portal for managing media, a local server for processing multimodal inputs, and an embodied robot client. PARTNER combines auditory, visual, and textual inputs using Whisper for speech transcription and a vision–language model (GPT-4o) that infers implicit affect from facial snapshots and dialogue history, rather than relying on rigid emotion classifiers. To enhance reproducibility and support future model training, PARTNER incorporates a real-time logging pipeline that synchronizes user inputs, sensor streams, and model outputs into a structured dataset. We provide a system-level evaluation on our robot, measuring end-to-end command–response latency, transcription accuracy, and dialogue coherence under varied sensing and environmental conditions. Our experiments show sub-3\,s loop latency on our testbed, robust transcription across various noise environments, and consistent responses during multi-turn dialogues, These findings validate PARTNER as a deployable platform for adaptive human–robot interaction. To our knowledge, PARTNER is the first Socially Assistive Robotics (SAR)-oriented system that (i) unifies a cloud portal for reminiscence media with a locally executed interaction server and an embodied agent, (ii) leverages VLM-based implicit affect cues for dialogue policy, and (iii) offers a real-time multimodal logging substrate to facilitate future domain-specific VLM/LLM fine-tuning.


# Summary. An optional shortened abstract.
summary: A distributed multimodal architecture for emotion-aware, personalized dialogue in socially assistive contexts.

tags:
  - ICRA

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # doi: 10.5555/123456
    # arxiv: 2512.00048v1
    

# Custom links
links:
  - type: pdf
    url: "https://drive.google.com/file/d/1yNf7-ZfjgdDV9E8fAKIjWLfNUeicJ8c1/view?usp=drive_link"
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://arxiv.org/abs/2512.00048
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
