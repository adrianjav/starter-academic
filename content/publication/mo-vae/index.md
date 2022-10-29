---
title: "Boosting heterogeneous VAEs via multi-objective optimization"
authors:
- admin
- Maryam Meghdadi
- Isabel Valera
date: "2021-12-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*NeurIPS 2021 Workshop: Your Model is Wrong: Robustness and misspecification in probabilistic modeling*"
publication_short: "*YMIW workshop*"

abstract: Variational autoencoders (VAEs) have been successfully applied to complex input data such as images and videos. Counterintuitively, their application to simpler, heterogeneous data—where features are of different types, often leads to underwhelming results. While the goal in the heterogeneous case is to accurately approximate all observed features, VAEs often perform poorly in a subset of them. In this work, we study this feature overlooking problem through the lens of multitask learning (MTL), relating it to the problem of negative transfer and the interaction between gradients from different features. With these new insights, we propose to train VAEs by leveraging off-the-shelf solutions from the MTL literature based on multi-objective optimization. Furthermore, we empirically demonstrate how these solutions significantly boost the performance of different VAE models and training objectives on a large variety of heterogeneous datasets.

# Summary. An optional shortened abstract.
summary: By leveraging MTL solutions for negative transfer, we improve the training dynamics of variational autoencoders (VAEs), boosting their performance on heterogeneous datasets.

tags:
- Variational autoencoders
- Deep Learning
- Probabilistic modeling
featured: false

links: []
url_pdf: uploads/movae/ymiw-paper.pdf
# url_code: https://github.com/fissoreg/relative-gradient-jacobian
# url_dataset: '#'
url_poster: uploads/movae/ymiw-poster.png
# url_project: ''
url_slides: uploads/movae/ymiw-slides.pdf
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Data reconstruction on a discrete variable.'
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

<!-- # Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

