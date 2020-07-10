---
title: "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction"
authors:
- Francesco Marchetti
- admin
- Lorenzo Seidenari
- Alberto Del Bimbo
date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2020*
publication_short: In *CVPR 2020*

abstract: "Autonomous vehicles are expected to drive in complex scenarios with several independent non cooperating agents. Path planning for safely navigating in such environments can not just rely on perceiving present location and motion of other agents. It requires instead to predict such variables in a far enough future. In this paper we address the problem of multimodal trajectory prediction exploiting a Memory Augmented Neural Network. Our method learns past and future trajectory embeddings using recurrent neural networks and exploits an associative external memory to store and retrieve such embeddings. Trajectory prediction is then performed by decoding in-memory future encodings conditioned with the observed past. We incorporate scene knowledge in the decoding state by learning a CNN on top of semantic scene maps.  Memory growth is limited by learning a writing controller based on the predictive capability of existing embeddings. We show that our method is able to natively perform multi-modal trajectory prediction obtaining state-of-the art results on three datasets. Moreover, thanks to the non-parametric nature of the memory module, we show how once trained our system can continuously improve by ingesting novel patterns."

# Summary. An optional shortened abstract.
summary: A key-value memory of past-future embeddings is leveraged for multiple future generation. It works in online learning and transfer learning scenarios.

tags:
- Autonomous Driving
- Trajectory Prediction
- Memory Networks
featured: true

links:
- name: Challenge
  url: https://youtu.be/Vcbj_peZT4Q?t=1131
- name: Arxiv
  url: https://arxiv.org/abs/2006.03340
- name: Journal Version
  url: publication/mantra/
url_pdf: http://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf
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
