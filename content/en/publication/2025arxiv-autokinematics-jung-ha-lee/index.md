---
title: "Data-Driven Dimensional Synthesis of Diverse Planar Four-bar Function Generation Mechanisms via Direct Parameterization"
authors:
- jaeheunjung
- WoonRyong Kim
- jeongunha
- admin
- Jae Kyung Shim
date: "2025-07-14T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'Dimensional synthesis of planar four-bar mechanisms is a challenging inverse problem in kinematics, requiring the determination of mechanism dimensions from desired motion specifications. We propose a data-driven framework that bypasses traditional equation-solving and optimization by leveraging supervised learning. Our method combines a synthetic dataset, an LSTM-based neural network for handling sequential precision points, and a Mixture of Experts (MoE) architecture tailored to different linkage types. Each expert model is trained on type-specific data and guided by a type-specifying layer, enabling both single-type and multi-type synthesis. A novel simulation metric evaluates prediction quality by comparing desired and generated motions. Experiments show our approach produces accurate, defect-free linkages across various configurations. This enables intuitive and efficient mechanism design, even for non-expert users, and opens new possibilities for scalable and flexible synthesis in kinematic design.'

# Summary. An optional shortened abstract.

tags:
- kinematics, machine learning, dimensional synthesis

links:

- name: PDF
  url: https://arxiv.org/pdf/2507.08269
# - name: Github
#   url: TODO
- name: arXiv
  url: https://arxiv.org/abs/2507.08269

# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: " Four-bar function generation mechanism"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
