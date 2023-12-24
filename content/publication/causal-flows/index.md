---
title: "Causal normalizing flows: from theory to practice"
authors:
  - admin
  - Pablo Sanchez-Martin
  - Isabel Valera
date: "2023-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Neural Information Processing Systems*"
publication_short: "*NeurIPS*"

abstract: "In this work, we deepen on the use of normalizing flows for causal reasoning. Specifically, we first leverage recent results on non-linear ICA to show that causal models are identifiable from observational data given a causal ordering, and thus can be recovered using autoregressive normalizing flows (NFs). Second, we analyze different design and learning choices for causal normalizing flows to capture the underlying causal data-generating process. Third, we describe how to implement the do-operator in causal NFs, and thus, how to answer interventional and counterfactual questions. Finally, in our experiments, we validate our design and training choices through a comprehensive ablation study; compare causal NFs to other approaches for approximating causal models; and empirically demonstrate that causal NFs can be used to address real-world problems, where the presence of mixed discrete-continuous data and partial knowledge on the causal graph is the norm."

# Summary. An optional shortened abstract.
summary: Armed with identifiability results, we demonstraste how to use normalizing flows to capture a causal model and perform causal inference with it.

tags:
- Normalziing flows
- Causal inference
featured: true

links: 
  - name: arXiv
    url: https://arxiv.org/abs/2306.05415
  - name: '<i class="fab fa-twitter"></i> thread'
    url: https://twitter.com/javaloyML/status/1667154628998230020
  # - name: Proceedings
  #   url: https://proceedings.mlr.press/v162/javaloy22a.html
# url_pdf: https://arxiv.org/pdf/2206.04496.pdf
url_code: https://github.com/psanch21/causal-flows
# url_dataset: '#'
url_poster: 'https://nips.cc/virtual/2023/poster/71711'
# url_project: ''
url_slides: 'http://adrianjav.github.io/uploads/causal-flow-oral-slides.pdf'
# url_source: '#'
# url_video: 'https://icml.cc/virtual/2022/spotlight/17492'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Prediction of a causal normalizing flows on the observational and interventional distributions of one variable of the German Credit dataset.'
  focal_point: "Smart"
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

<!-- # Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

