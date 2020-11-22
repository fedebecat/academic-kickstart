---
title: "Multiple Future Prediction Leveraging Synthetic Trajectories"
authors:
- Lorenzo Berlincioni
- admin
- Lorenzo Seidenari
- Alberto Del Bimbo
date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 25th International Conference on Pattern Recognition (ICPR)*
publication_short: In *ICPR 2020*

abstract: "Trajectory prediction is an important task, especially in autonomous driving. The ability to forecast the position of other moving agents can yield to an effective planning, ensuring safety for the autonomous vehicle as well for the observed entities. In this work we propose a data driven approach based on Markov Chains to generate synthetic trajectories, which are useful for training a multiple future trajectory predictor. The advantages are twofold: on the one hand synthetic samples can be used to augment existing datasets and train more effective predictors; on the other hand, it allows to generate samples with multiple ground truths, corresponding to diverse equally likely outcomes of the observed trajectory. We define a trajectory prediction model and a loss that explicitly address the multimodality of the problem and we show that combining synthetic and real data leads to prediction improvements, obtaining state of the art results."

# Summary. An optional shortened abstract.
summary: Synthetic trajectories are generated via a Markov Chain estimated from real data. Multimodal synthetic data allow us to exploit supervision on multiple futures and improve forecasting models.

tags:
- Autonomous driving
- Deep Learinig
- Markov Chain
- Synthetic data
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/2010.08948
url_pdf: https://arxiv.org/pdf/2010.08948.pdf
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
