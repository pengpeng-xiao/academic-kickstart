---
title: "Quantum DeepONet: Neural operators accelerated by quantum computing"
authors:
- admin
- Muqing Zheng
- Anran Jiao
- Xiu Yang
- Lu Lu
date: "2024-09-24T00:00:00Z"
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

abstract: In the realm of computational science and engineering, constructing models that reflect real-world phenomena requires solving partial differential equations (PDEs) with different conditions. Recent advancements in neural operators, such as deep operator network (DeepONet), which learn mappings between infinite-dimensional function spaces, promise efficient computation of PDE solutions for a new condition in a single forward pass. However, classical DeepONet entails quadratic complexity concerning input dimensions during evaluation. Given the progress in quantum algorithms and hardware, here we propose to utilize quantum computing to accelerate DeepONet evaluations, yielding complexity that is linear in input dimensions. Our proposed quantum DeepONet integrates unary encoding and orthogonal quantum layers. We benchmark our quantum DeepONet using a variety of PDEs, including the antiderivative operator, advection equation, and Burgers' equation. We demonstrate the method's efficacy in both ideal and noisy conditions. Furthermore, we show that our quantum DeepONet can also be informed by physics, minimizing its reliance on extensive data collection. Quantum DeepONet will be particularly advantageous in applications in outer loop problems which require to explore parameter space and solving the corresponding PDEs, such as uncertainty quantification and optimal experimental design.

# Summary. An optional shortened abstract.
summary: 

tags:
- Quantum machine learning 
- Operator learning

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2409.15683
url_code: ''
url_dataset: ''
url_poster: "/publication/quantum_deeponet/quantum_deeponet_poster.pdf"
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=54orRsJuFrU&t=67s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Architecture of quantum DeepONet'
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
