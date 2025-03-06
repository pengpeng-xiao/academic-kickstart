---
title: "LD-EnSF: Synergizing Latent Dynamics with Ensemble Score Filters for Fast Data Assimilation with Sparse Observations"
authors:
- admin
- Phillip Si
- Peng Chen

date: "2024-11-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Data assimilation techniques are crucial for correcting trajectories when modeling complex physical systems. The Latent Ensemble Score Filter (Latent-EnSF), a recently developed data assimilation method, has shown great promise in high-dimensional and nonlinear data assimilation problems with sparse observations. However, this method faces the challenge of high computational cost due to the expensive forward simulation. In this paper, we introduce Latent Dynamics EnSF (LD-EnSF), a novel methodology that evolves the dynamics in a low-dimensional latent space and significantly accelerates the data assimilation process. To achieve this, we introduce a novel variant of Latent Dynamics Networks (LDNets) to effectively capture the system's dynamics within a low-dimensional latent space. Additionally, we propose a new method for encoding sparse observations into the latent space using LSTM networks. We demonstrate the robustness, accuracy, and efficiency of the proposed method for two challenging dynamical systems with highly sparse (in both space and time) and noisy observations.

# Summary. An optional shortened abstract.
summary: 

tags:
- Latent Dynamics
- Data Assimilation

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2411.19305
url_code: ''
url_dataset: ''
url_poster: ""
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The pipeline of the LD-EnSF method'
  focal_point: "center"
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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
