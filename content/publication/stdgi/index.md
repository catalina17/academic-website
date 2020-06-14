---
title: "Spatio-Temporal Deep Graph Infomax"
authors:
- Felix L. Opolka
- Aaron Solomon
- admin
- Petar Veličković
- Pietro Liò
- R Devon Hjelm
date: "2019-04-01:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: _Representation Learning on Graphs and Manifolds (RLGM) Workshop (ICLR 2019)_
publication_short: RLGM Workshop (ICLR 2019)

abstract: "Spatio-temporal graphs such as traffic networks or gene regulatory systems present challenges for the existing deep learning methods due to the complexity of structural changes over time. To address these issues, we introduce Spatio-Temporal Deep Graph Infomax (STDGI) - a fully unsupervised node representation learning approach based on mutual information maximization that exploits both the temporal and spatial dynamics of the graph. Our model tackles the challenging task of node-level regression by training embeddings to maximize the mutual information between patches of the graph, at any given time step, and between features of the central nodes of patches, in the future. We demonstrate through experiments and qualitative studies that the learned representations can successfully encode relevant information about the input graph and improve the predictive performance of spatio-temporal auto-regressive forecasting models."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- graphs
- unsupervised
- infomax
- spatio-temporal
- deep graph infomax
- DGI
- graph neural networks
featured: false

links:
url_pdf: https://arxiv.org/pdf/1904.06316
# url_code: https://github.com/catalina17/XFlow/
# url_dataset: https://www.cl.cam.ac.uk/~ccc53/files/digits.tar.gz
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "STDGI unsupervised training."
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
