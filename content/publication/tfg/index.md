---
title: "Preliminary Results on Different Text Processing Tasks Using Encoder-Decoder Networks and the Causal Feature Extractor"
authors:
- admin
- Gines García Mateos
date: "2020-08-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-22-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Multidisciplinary Digital Publishing Institute*"
publication_short: "*MDPI*"

abstract: "Deep learning methods are gaining popularity in different application domains, and especially in natural language processing. It is commonly believed that using a large enough dataset and an adequate network architecture, almost any processing problem can be solved. A frequent and widely used typology is the encoder-decoder architecture, where the input data is transformed into an intermediate code by means of an encoder, and then a decoder takes this code to produce its output. Different types of networks can be used in the encoder and the decoder, depending on the problem of interest, such as convolutional neural networks (CNN) or long-short term memories (LSTM). This paper uses for the encoder a method recently proposed, called Causal Feature Extractor (CFE). It is based on causal convolutions (i.e., convolutions that depend only on one direction of the input), dilatation (i.e., increasing the aperture size of the convolutions) and bidirectionality (i.e., independent networks in both directions). Some preliminary results are presented on three different tasks and compared with state-of-the-art methods: bilingual translation, LaTeX decompilation and audio transcription. The proposed method achieves promising results, showing its ubiquity to work with text, audio and images. Moreover, it has a shorter training time, requiring less time per iteration, and a good use of the attention mechanisms based on attention matrices."

# Summary. An optional shortened abstract.
summary: We test the Causal Feature Extractor in a series of different scenarios (text/image/audio) and show its great versability with minimal fine-tuning.

tags:
- text normalization
- "encoder-decoder"
- deep learning
featured: false

links:
url_pdf: https://www.mdpi.com/2076-3417/10/17/5772/pdf
url_code: ""
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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


