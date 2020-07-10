---
title: "Am I done? Predicting action progress in videos"
authors:
- admin
- Tiberio Uricchio
- Lorenzo Seidenari
- Alberto Del Bimbo
- Lamberto Ballan
date: "2020-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)*
publication_short: In *TOMM*

abstract: "In this paper we deal with the problem of predicting action progress in videos. We argue that this is an extremely important task since it can be valuable for a wide range of interaction applications. To this end we introduce a novel approach, named ProgressNet, capable of predicting when an action takes place in a video, where it is located within the frames, and how far it has progressed during its execution. To provide a general definition of action progress, we ground our work in the linguistics literature, borrowing terms and concepts to understand which actions can be the subject of progress estimation. As a result, we define a categorization of actions and their phases. Motivated by the recent success obtained from the interaction of Convolutional and Recurrent Neural Networks, our model is based on a combination of the Faster R-CNN framework, to make frame-wise predictions, and LSTM networks, to estimate action progress through time. After introducing two evaluation protocols for the task at hand, we demonstrate the capability of our model to effectively predict action progress on the UCF-101 and J-HMDB datasets."

# Summary. An optional shortened abstract.
summary: Progress prediction of actions and phases in videos

tags:
- Action Recognition
- Action Progress
- Linguistics
featured: true

links:
- name: Arxiv
  url: https://arxiv.org/abs/1705.01781
#url_pdf: https://dl.acm.org/doi/pdf/10.1145/3343031.3350598
#url_code: '#'
#url_dataset: '#'
#url_poster: 'poster_acmmm_becattini.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=aryhiDMbhT8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: "center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- research

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
