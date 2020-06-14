---
title: "Towards Sparse Hierarchical Graph Classifiers"
authors:
- Cătălina Cangea*
- Petar Veličković*
- Nikola Jovanović
- Thomas Kipf
- Pietro Liò
date: "2019-11-01:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: _Workshop on Relational Representation Learning (NeurIPS 2018)_
publication_short: R2L workshop (NeurIPS 2018)

abstract: "Recent advances in representation learning on graphs, mainly leveraging graph convolutional networks, have brought a substantial improvement on many graph-based benchmark tasks. While novel approaches to learning node embeddings are highly suitable for node classification and link prediction, their application to graph classification (predicting a single label for the entire graph) remains mostly rudimentary, typically using a single global pooling step to aggregate node features or a hand-designed, fixed heuristic for hierarchical coarsening of the graph structure. An important step towards ameliorating this is differentiable graph coarsening---the ability to reduce the size of the graph in an adaptive, data-dependent manner within a graph neural network pipeline, analogous to image downsampling within CNNs. However, the previous prominent approach to pooling has quadratic memory requirements during training and is therefore not scalable to large graphs. Here we combine several recent advances in graph neural network design to demonstrate that competitive hierarchical graph classification results are possible without sacrificing sparsity. Our results are verified on several established graph classification benchmarks, and highlight an important direction for future research in graph-based neural networks."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- graph neural networks
- graph classification
- GNN
- pooling
- sparse
- hierarchical
featured: false

links:
url_pdf: https://arxiv.org/pdf/1811.01287.pdf
# url_code: https://github.com/catalina17/XFlow/
# url_dataset: https://www.cl.cam.ac.uk/~ccc53/files/digits.tar.gz
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Overview of our sparse pooling GNN architecture."
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
