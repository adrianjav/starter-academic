---
title: "Lipschitz standardization for multivariate learning"
authors:
- admin
- Isabel Valera
date: "2020-10-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-22-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Probabilistic learning is increasingly being tackled as an optimization problem, with gradient-based approaches as predominant methods. When modeling multivariate likelihoods, a usual but undesirable outcome is that the learned model fits only a subset of the observed variables, overlooking the rest. In this work, we study this problem through the lens of multitask learning (MTL), where similar effects have been broadly studied. While MTL solutions do not directly apply in the probabilistic setting (as they cannot handle the likelihood constraints) we show that similar ideas may be leveraged during data preprocessing. First, we show that data standardization often helps under common continuous likelihoods, but it is not enough in the general case, specially under mixed continuous and discrete likelihood models. In order for balance multivariate learning, we then propose a novel data preprocessing, Lipschitz standardization, which balances the local Lipschitz smoothness across variables. Our experiments on real-world datasets show that Lipschitz standardization leads to more accurate multivariate models than the ones learned using existing data preprocessing techniques.

# Summary. An optional shortened abstract.
summary: We propose a new preprocessing method for first-order optimized probabilistic models that eases a more balanced learning across variables when modeling heterogeneous multivariate likelihoods.

tags:
- preprocesssing
- lipschitz-standardization
- balanced learning
- heterogeneous data
featured: false

links:
- name: arxiv
  url: https://arxiv.org/abs/2002.11369
url_pdf: https://arxiv.org/pdf/2002.11369.pdf
url_code: https://github.com/adrianjav/lipschitz-standardization
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Illustrative example of unbalanced learning.'
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


