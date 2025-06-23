---
title: An Exactly Solvable Model for Emergence and Scaling Laws in the Multitask Sparse Parity Problem

event: AIML@K Seminar Series
event_url: https://aiml-k.github.io/tag/seminar/  
tags: ['seminar']

location: Room 526, Asan Science Building 
address:
  street: 145 Anam-ro
  city: Seongbuk-gu, Seoul
  # region: CA
  postcode: '02841'
  country: South Korea

summary: 'Can an analytically solvable model explain emergent behaviors and scaling laws in multitask learning, showing how new skills appear as training progresses?'
abstract: |
  Deep learning models can exhibit what appears to be a sudden ability to solve a new problem as training time, training data, or model size increases, a phenomenon known as emergence. In this paper, we present a framework where each new ability (a skill) is represented as a basis function. We solve a simple multi-linear model in this skill-basis, finding analytic expressions for the emergence of new skills, as well as for scaling laws of the loss with training time, data size, model size, and optimal compute. We compare our detailed calculations to direct simulations of a two-layer neural network trained on multitask sparse parity, where the tasks in the dataset are distributed according to a power-law. Our simple model captures, using a single fit parameter, the sigmoidal emergence of multiple new skills as training time, data size or model size increases in the neural network.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-17T13:00:00+09:00'
date_end: '2025-06-17T14:00:00+09:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-10T00:00:00Z'

authors: ['Seok Hyeong Lee']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Dr. Seok Hyeong Lee gives a talk on his **[work in NeurIPS 2024](https://neurips.cc/virtual/2024/poster/94372)**'
#   focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
url_poster: ''

links:
- name: NeurIPS
  url: https://proceedings.neurips.cc/paper_files/paper/2024/hash/45f7ad60c01f17711ccd8ac2f2fb77e3-Abstract-Conference.html
- name: Poster
  url: https://neurips.cc/media/PosterPDFs/NeurIPS%202024/94372.png?t=1731019890.6678758
- name: ArXiv
  url: https://arxiv.org/abs/2404.17563

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

<!-- 
Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page. -->
