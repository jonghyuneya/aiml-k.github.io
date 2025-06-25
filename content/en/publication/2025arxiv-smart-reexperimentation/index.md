---
title: "Re-experiment Smart: a Novel Method to Enhance Data-driven Prediction of Mechanical Properties of Epoxy Polymers"
authors:
- wanshancui
- yejinjeong
- Inwook Song
- Gyuri Kim
- Minsang Kwon
- admin
date: "2025-06-04T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'Accurate prediction of polymer material properties through data-driven approaches greatly accelerates novel material development by reducing redundant experiments and trial-and-error processes. However, inevitable outliers in empirical measurements can severely skew machine learning results, leading to erroneous prediction models and suboptimal material designs. To address this limitation, we propose a novel approach to enhance dataset quality efficiently by integrating multi-algorithm outlier detection with selective re-experimentation of unreliable outlier cases. To validate the empirical effectiveness of the approach, we systematically construct a new dataset containing 701 measurements of three key mechanical properties: glass transition temperature (T_g), tan δ peak, and crosslinking density (v_c). To demonstrate its general applicability, we report the performance improvements across multiple machine learning models, including Elastic Net, SVR, Random Forest, and TPOT, to predict the three key properties. Our method reliably reduces prediction error (RMSE) and significantly improves accuracy with minimal additional experimental work, requiring only about 5% of the dataset to be re-measured. These findings highlight the importance of data quality enhancement in achieving reliable machine learning applications in polymer science and present a scalable strategy for improving predictive reliability in materials science.'

# Summary. An optional shortened abstract.
summary: 'We propose a data quality enhancement strategy combining multi-algorithm outlier detection with selective re-experimentation, significantly improving machine learning prediction accuracy for epoxy mechanical properties with minimal additional experimentation.'

tags:
- Material Science
- Outlier Detection

links:

- name: PDF
  url: https://arxiv.org/pdf/2506.01994
# - name: Github
#   url: TODO
- name: arXiv
  url: https://arxiv.org/abs/2506.01994

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
  caption: "Smart re-experimentation to control outlier effects on ML in material science"
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
