---
title: "Exploiting multimodality and structure in world representations"
authors:
- admin
date: "2021-03-07:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Doctoral thesis, University of Cambridge (2021)
publication_short: _PhD thesis (2021)_

abstract: "An essential aim of artificial intelligence research is to design agents that will eventually cooperate with humans within the real world. To this end, embodied learning is emerging as one of the most important efforts contributed by the machine learning community towards this goal. Recently developing sub-fields concern various aspects of such systems---visual reasoning, language representations, causal mechanisms, robustness to out-of-distribution inputs, to name only a few. In particular, multimodal learning and language grounding are vital to achieving a strong understanding of the real world. Humans build internal representations via interacting with their environment, learning complex associations between visual, auditory and linguistic concepts. Since the world abounds with structure, graph-based encodings are also likely to be incorporated in reasoning and decision-making modules. Furthermore, these relational representations are rather symbolic in nature---providing advantages over other formats, such as raw pixels---and can encode various types of links (temporal, causal, spatial) which can be essential for understanding and acting in the real world. This thesis presents three research works that study and develop likely aspects of future intelligent agents. The first contribution centers on vision-and-language learning, introducing a challenging embodied task that shifts the focus of an existing one to the visual reasoning problem. By extending popular visual question answering (VQA) paradigms, I also designed several models that were evaluated on the novel dataset. This produced initial performance estimates for environment understanding, through the lens of a more challenging VQA downstream task. The second work presents two ways of obtaining hierarchical representations of graph-structured data. These methods either scaled to much larger graphs than the ones processed by the best-performing method at the time, or incorporated theoretical properties via the use of topological data analysis algorithms. Both approaches competed with contemporary state-of-the-art graph classification methods, even outside social domains in the second case, where the inductive bias was PageRank-driven. Finally, the third contribution delves further into relational learning, presenting a probabilistic treatment of graph representations in complex settings such as few-shot, multi-task learning and scarce-labelled data regimes. By adding relational inductive biases to neural processes, the resulting framework can model an entire distribution of functions which generate datasets with structure. This yielded significant performance gains, especially in the aforementioned complex scenarios, with semantically-accurate uncertainty estimates that drastically improved over the neural process baseline. This type of framework may eventually contribute to developing lifelong-learning systems, due to its ability to adapt to novel tasks and distributions. The benchmark, methods and frameworks that I have devised during my doctoral studies suggest important future directions for embodied and graph representation learning research. These areas have increasingly proved their relevance to designing intelligent and collaborative agents, which we may interact with in the near future. By addressing several challenges in this problem space, my contributions therefore take a few steps towards building machine learning systems to be deployed in real-life settings."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- machine learning
- embodied learning
- graph neural networks
- graph pooling
- graph classification
- node classification
- neural processes
- visual question answering
- language grounding
- meta-learning
- few-shot learning
featured: false

links:
url_pdf: https://doi.org/10.17863/CAM.72490
# url_code: ''
# url_dataset: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "An illustration of the three aspects explored in this thesis that can benefit world representations."
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
