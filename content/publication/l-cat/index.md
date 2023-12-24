---
title: "Learnable Graph Convolutional Attention Networks"
authors:
  - admin
  - Pablo Sanchez-Martin
  - Amit Levi
  - Isabel Valera
date: "2023-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Learning Representations*"
publication_short: "*ICLR*"

abstract: "Existing Graph Neural Networks (GNNs) compute the message exchange between nodes by either aggregating uniformly (convolving) the features of all the neighboring nodes, or by applying a non-uniform score (attending) to the features. Recent works have shown the strengths and weaknesses of the resulting GNN architectures, respectively, GCNs and GATs. In this work, we aim at exploiting the strengths of both approaches to their full extent. To this end, we first introduce the graph convolutional attention layer (CAT), which relies on convolutions to compute the attention scores. Unfortunately, as in the case of GCNs and GATs, we show that there exists no clear winner between the three (neither theoretically nor in practice) as their performance directly depends on the nature of the data (i.e., of the graph and features). This result brings us to the main contribution of our work, the learnable graph convolutional attention network (L-CAT): a GNN architecture that automatically interpolates between GCN, GAT and CAT in each layer, by adding only two scalar parameters. Our results demonstrate that L-CAT is able to efficiently combine different GNN layers along the network, outperforming competing methods in a wide range of datasets, and resulting in a more robust model that reduces the need of cross-validating."

# Summary. An optional shortened abstract.
summary: We theoretically show that there is no free-lunch for different types of message-passing GNNs, including the one we propose, and introduce a data-driven way of learning to interpolate across them.

tags:
- Graph Neural Networks
featured: true

links: 
  - name: arXiv
    url: https://arxiv.org/abs/2211.11853
  - name: '<i class="fab fa-twitter"></i> thread'
    url: https://twitter.com/ML_pablosm/status/1595436539634401283
  - name: Proceedings
    url: https://openreview.net/forum?id=WsUMeHPo-2
# url_pdf: https://arxiv.org/pdf/2206.04496.pdf
url_code: https://github.com/psanch21/LCAT
# url_dataset: '#'
# url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202022/b7da6669894867f04b8727876a69ffc0.png'
# url_project: ''
# url_slides: 'https://icml.cc/media/icml-2022/Slides/17492.pdf'
# url_source: '#'
# url_video: 'https://icml.cc/virtual/2022/spotlight/17492'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Different types of GNNs perform better depending on the characteristics of the dataset.'
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

