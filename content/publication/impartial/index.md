---
title: "Mitigating Modality Collapse in Multimodal VAEs via Impartial Optimization"
authors:
  - admin
  - Maryam Meghdadi
  - Isabel Valera
date: "2022-09-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Mitigating Modality Collapse in Multimodal VAEs via Impartial Optimization"
publication_short: "Mitigating Modality Collapse in Multimodal VAEs"

abstract: "A number of variational autoencoders (VAEs) have recently emerged with the aim of modeling multimodal data, e.g., to jointly model images and their corresponding captions. Still, multimodal VAEs tend to focus solely on a subset of the modalities, e.g., by fitting the image while neglecting the caption. We refer to this limitation as modality collapse. In this work, we argue that this effect is a consequence of conflicting gradients during multimodal VAE training. We show how to detect the sub-graphs in the computational graphs where gradients conflict (impartiality blocks), as well as how to leverage existing gradient-conflict solutions from multitask learning to mitigate modality collapse. That is, to ensure impartial optimization across modalities. We apply our training framework to several multimodal VAE models, losses and datasets from the literature, and empirically show that our framework significantly improves the reconstruction performance, conditional generation, and coherence of the latent space across modalities."

# Summary. An optional shortened abstract.
summary: We connect the problem of modality collapse with conflicting gradients, and leverage solutions from multitask learning to alleviate it.

tags:
- Variational autoencoders
- Heterogeneous data
- Conflicting gradients
- Multitask Learning
featured: true

links: 
  - name: arXiv
    url: https://arxiv.org/abs/2206.04496
  - name: Thread
    url: https://twitter.com/javaloyML/status/1536299712881500163
  - name: ICML proceedings
    url: https://proceedings.mlr.press/v162/javaloy22a.html
# url_pdf: https://arxiv.org/pdf/2206.04496.pdf
url_code: https://media.icml.cc/Conferences/ICML2022/supplementary/javaloy22a-supp.zip
# url_dataset: '#'
url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202022/b7da6669894867f04b8727876a69ffc0.png'
# url_project: ''
url_slides: 'https://icml.cc/media/icml-2022/Slides/17492.pdf'
# url_source: '#'
url_video: 'https://icml.cc/virtual/2022/spotlight/17492'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Simple multimodal VAE computational graph, explicitly exposing its impartiality block.'
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

