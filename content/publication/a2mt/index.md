---
title: "Active Acquisition for Multimodal Temporal Data: A Challenging Decision-Making Task"
authors:
- Jannik Kossen
- Cătălina Cangea
- Eszter Vértes
- Andrew Jaegle
- Viorica Patraucean
- Ira Ktena
- Nenad Tomasev
- Danielle Belgrave
date: "2023-06-30:00:00Z"
# doi: "https://doi.org/10.17863/CAM.72490"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Transactions on Machine Learning Research
publication_short: _TMLR 2023_

abstract: "We introduce a challenging decision-making task that we call active acquisition for multimodal temporal data (A2MT). In many real-world scenarios, input features are not readily available at test time and must instead be acquired at significant cost. With A2MT, we aim to learn agents that actively select which modalities of an input to acquire, trading off acquisition cost and predictive performance. A2MT extends a previous task called active feature acquisition to temporal decision making about high-dimensional inputs. Further, we propose a method based on the Perceiver IO architecture to address A2MT in practice. Our agents are able to solve a novel synthetic scenario requiring practically relevant cross-modal reasoning skills. On two large-scale, real-world datasets, Kinetics-700 and AudioSet, our agents successfully learn cost-reactive acquisition behavior. However, an ablation reveals they are unable to learn to learn adaptive acquisition strategies, emphasizing the difficulty of the task even for state-of-the-art models. Applications of A2MT may be impactful in domains like medicine, robotics, or finance, where modalities differ in acquisition cost and informativeness."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- perceiver
- active feature acquisition
- multimodal
- temporal
- classification
- large-scale
- high-dimensional inputs
featured: true

links:
url_pdf: https://openreview.net/pdf?id=Gbu1bHQhEL
# url_code: https://github.com/google-research/perceiver-ar
# url_dataset: ''
url_project: https://www.deepmind.com/publications/active-acquisition-for-multimodal-temporal-data-a-challenging-decision-making-task
# url_slides: ''
# url_source: ''
# url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "In many practical applications, features are not available a priori at test time and have to be acquired at a real-world cost to allow for the prediction of an associated label. In Active Acquisition for Multimodal Temporal Data, we aim to learn agents that efficiently acquire for multimodal temporal inputs."
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
