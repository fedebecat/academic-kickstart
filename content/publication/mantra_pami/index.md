---
title: "Multiple Trajectory Prediction of Moving Agents with Memory Augmented Networks"
authors:
- Francesco Marchetti
- admin
- Lorenzo Seidenari
- Alberto Del Bimbo
date: "2020-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *CVPR 2020*

abstract: "Pedestrians and drivers are expected to safely navigate complex urban environments along with several non cooperating agents. Autonomous vehicles will soon replicate this capability. Each agent acquires a representation of the world from an egocentric perspective and must make decisions ensuring safety for itself and others. This requires to predict motion patterns of observed agents for a far enough future. In this paper we propose MANTRA, a model that exploits memory augmented networks to effectively predict multiple trajectories of other agents, observed from an egocentric perspective. Our model stores observations in memory and uses trained controllers to write meaningful pattern encodings and read trajectories that are most likely to occur in future. We show that our method is able to natively perform multi-modal trajectory prediction obtaining state-of-the art results on four datasets. Moreover, thanks to the non-parametric nature of the memory module, we show how once trained our system can continuously improve by ingesting novel patterns."

# Summary. An optional shortened abstract.
summary: A key-value memory of past-context-future embeddings is leveraged for multiple future generation. It works in online learning and transfer learning scenarios.

tags:
- Autonomous Driving
- Trajectory Prediction
- Memory Networks
featured: false

links:
- name: Challenge
  url: https://youtu.be/Vcbj_peZT4Q?t=1131
url_pdf: http://www.micc.unifi.it/seidenari/wp-content/papercite-data/pdf/tpami20.pdf
#url_code: '#' 
url_dataset: https://github.com/Marchetz/KITTI-trajectory-prediction
#url_poster: 'poster_acmmm_becattini.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=_Edlt3Pbn3M'

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
- Autonomous Driving

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
