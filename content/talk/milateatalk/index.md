---
title: "Question Answering in Realistic Visual Environments: Challenges and Approaches"
event: Mila Tea Talk
event_url: https://mila.quebec/en/cours/rdv/

location: Mila
address:
  street: 6666 St-Urbain
  city: Montreal
  region: QC
  postcode: H2S 3H1
  country: Canada

summary: An overview of challenging QA tasks and an alternative take on EQA.
abstract: "The Embodied Question Answering (EQA) and Interactive Question Answering (IQA) tasks were recently introduced as a means to study the capabilities of agents in rich, realistic 3D environments, requiring both navigation and reasoning to achieve success. Each of these skills typically needs a different approach, which should nevertheless be smoothly integrated with the rest of the system leveraged by the agent. However, initial approaches either suffer from potentially weaker performance than when using a language-only model or are preceded by additional hand-engineered steps. This talk will provide an overview of the existing work on this thread and describe in more detail our recent study published at BMVC 2019 and accepted at ViGIL 2019, [VideoNavQA: Bridging the Gap between Visual and Embodied Question Answering](https://arxiv.org/abs/1908.04950). Here, we investigate the feasibility of EQA -type tasks by building a novel benchmark, which contains pairs of questions and videos generated in the House3D environment. While removing the navigation and action selection requirements from EQA , we increase the difficulty of the visual reasoning component via a much larger question space, tackling the sort of complex reasoning questions that make QA tasks challenging. By designing and evaluating several VQA -style models on the dataset, we establish a novel way of evaluating EQA feasibility given existing methods, while highlighting the difficulty of the problem even in the most ideal setting."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-10-25T10:30:00Z"
# date_end: "2019-10-25T11:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-10-13T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/catalinacangea
url_code: https://github.com/catalina17/VideoNavQA/
url_pdf: https://arxiv.org/abs/1908.04950
url_slides: https://drive.google.com/file/d/10J1xw3L2WOqE5n7xX5uISlXZwy_r9ElS
url_video: "https://bluejeans.com/playback/s/Upy6gtNPO2HLTzQ1D9l87GqB37HxqvyvSM8Wg6nxBQCAAog6WFNXS0WJo8zTg8Zq"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---
