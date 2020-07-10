---
title: "Explaining Autonomous Driving by Learning End-to-End Visual Attention "
authors:
- Luca Cultrera
- Lorenzo Seidenari
- admin
- Pietro Pala
- Alberto Del Bimbo
date: "2020-06-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2020 Workshop on Safe Artificial Intelligence for Automated Driving*
publication_short: In *CVPR 2020*

abstract: "Current deep learning based autonomous driving approaches yield impressive results also leading to in-production deployment in certain controlled scenarios. One of the most popular and fascinating approaches relies on learning vehicle controls directly from data perceived by sensors. This end-to-end learning paradigm can be applied both in classical supervised settings and using reinforcement learning. Nonetheless the main drawback of this approach as also in other learning problems is the lack of explainability. Indeed, a deep network will act as a black-box outputting predictions depending on previously seen driving patterns without giving any feedback on why such decisions were taken. While to obtain optimal performance it is not critical to obtain explainable outputs from a learned agent, especially in such a safety critical field, it is of paramount importance to understand how the network behaves. This is particularly relevant to interpret failures of such systems. In this work we propose to train an imitation learning based agent equipped with an attention model. The attention model allows us to understand what part of the image has been deemed most important. Interestingly, the use of attention also leads to superior performance in a standard benchmark using the CARLA driving simulator."

# Summary. An optional shortened abstract.
summary: Visual attention is used to enhance an imitation learning agent, obtaining improved results and explainable driving decisions in the CARLA simulator.

tags:
- Autonomous driving
- Explainable AI
- Attention
- Imitation Learning
- CARLA
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/2006.03347
url_pdf: http://openaccess.thecvf.com/content_CVPRW_2020/papers/w20/Cultrera_Explaining_Autonomous_Driving_by_Learning_End-to-End_Visual_Attention_CVPRW_2020_paper.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: 'poster_acmmm_becattini.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: 'https://www.youtube.com/watch?v=aryhiDMbhT8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: "top"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- research
- Autonomous Driving

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
