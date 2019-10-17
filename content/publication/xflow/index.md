---
title: "XFlow: Cross-modal Deep Neural Networks for Audiovisual Classification"
authors:
- admin
- Petar Veličković
- Pietro Liò
date: "2019-04-01:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: To appear in *IEEE Transactions on Neural Networks and Learning Systems*
publication_short: To appear in *IEEE TNNLS*

abstract: "In recent years, there have been numerous developments towards solving multimodal tasks, aiming to learn a stronger representation than through a single modality. Certain aspects of the data can be particularly useful in this case - for example, correlations in the space or time domain across modalities - but should be wisely exploited in order to benefit from their full predictive potential. We propose two deep learning architectures with multimodal cross-connections that allow for dataflow between several feature extractors (XFlow). Our models derive more interpretable features and achieve better performances than models which do not exchange representations, usefully exploiting correlations between audio and visual data, which have a different dimensionality and are nontrivially exchangeable. Our work improves on existing multimodal deep learning algorithms in two essential ways: (1) it presents a novel method for performing cross-modality (before features are learned from individual modalities) and (2) extends the previously proposed cross-connections which only transfer information between streams that process compatible data. Illustrating some of the representations learned by the connections, we analyse their contribution to the increase in discrimination ability and reveal their compatibility with a lip-reading network intermediate representation. We provide the research community with Digits, a new dataset consisting of three data types extracted from videos of people saying the digits 0-9. Results show that both cross-modal architectures outperform their baselines (by up to 11.5%) when evaluated on the AVletters, CUAVE and Digits datasets, achieving state-of-the-art results.

A shorter version was also presented at the Workshop on Computational Models for Crossmodal Learning (CMCML) at The 7th Joint IEEE International Conference on Development and Learning and on Epigenetic Robotics (IEEE ICDL-EPIROB 2017) and at the ARM Research Summit 2017."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- cross-modality
- audio
- video
- cross-connections
- speech processing
- audiovisual classification
- MFCCs
- dataset
- benchmark
- Digits
featured: false

links:
url_pdf: https://arxiv.org/pdf/1709.00572.pdf
url_code: https://github.com/catalina17/XFlow/
url_dataset: https://www.cl.cam.ac.uk/~ccc53/files/digits.tar.gz
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "High-level description of the XFlow architecture."
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
