---
title: "General-purpose, long-context autoregressive modeling with Perceiver AR"
authors:
- Curtis Hawthorne*
- Andrew Jaegle*
- Cătălina Cangea
- Sebastian Borgeaud
- Charlie Nash
- Mateusz Malinowski
- Sander Dieleman
- Oriol Vinyals
- Matthew Botvinick
- Ian Simon
- Hannah Sheahan
- Neil Zeghidour
- Jean-Baptiste Alayrac*
- João Carreira*
- Jesse Engel*
date: "2022-03-25:00:00Z"
# doi: "https://doi.org/10.17863/CAM.72490"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Thirty-ninth International Conference on Machine Learning
publication_short: _ICML 2022_

abstract: "Real-world data is high-dimensional: a book, image, or musical performance can easily contain hundreds of thousands of elements even after compression. However, the most commonly used autoregressive models, Transformers, are prohibitively expensive to scale to the number of inputs and layers needed to capture this long-range structure. We develop Perceiver AR, an autoregressive, modality-agnostic architecture which uses cross-attention to map long-range inputs to a small number of latents while also maintaining end-to-end causal masking. Perceiver AR can directly attend to over a hundred thousand tokens, enabling practical long-context density estimation without the need for hand-crafted sparsity patterns or memory mechanisms. When trained on images or music, Perceiver AR generates outputs with clear long-term coherence and structure. Our architecture also obtains state-of-the-art likelihood on long-sequence benchmarks, including 64 x 64 ImageNet images and PG-19 books."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- perceiver
- autoregressive
- density estimation
- image generation
- language modelling
- music generation
- soundstream
- symbolic
- maestro
featured: true

links:
url_pdf: https://arxiv.org/pdf/2202.07765.pdf
url_code: https://github.com/google-research/perceiver-ar
# url_dataset: ''
url_project: https://magenta.tensorflow.org/perceiver-ar
# url_slides: ''
# url_source: ''
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Perceiver AR initial cross-attend followed by the stack of self-attention layers which refines the latents to predict future tokens."
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
