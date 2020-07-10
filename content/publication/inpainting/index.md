---
title: "Road layout understanding by generative adversarial inpainting"
authors:
- Lorenzo Berlincioni
- admin
- Leonardo Galteri
- Lorenzo Seidenari
- Alberto Del Bimbo
date: "2019-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: In *Inpainting and Denoising Challenges 2019*
publication_short: In *Chalearn 2019*

abstract: Autonomous driving is becoming a reality, yet vehicles still need to rely on complex sensor fusion to understand the scene they act in. The ability to discern static environment and dynamic entities provides a comprehension of the road layout that poses constraints to the reasoning process about moving objects. We pursue this through a GAN-based semantic segmentation inpainting model to remove all dynamic objects from the scene and focus on understanding its static components such as streets, sidewalks and buildings. We evaluate this task on the Cityscapes dataset and on a novel synthetically generated dataset obtained with the CARLA simulator and specifically designed to quantitatively evaluate semantic segmentation inpaintings. We compare our methods with a variety of baselines working both in the RGB and segmentation domains.

# Summary. An optional shortened abstract.
summary: Semantic segmentation inpainting to remove occlusions due to dynamic objects and recover the road layout.

tags:
- Inpainting
- Autonomous Driving
- Semantic Segmentation
- Automotive
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/1805.11746
url_pdf: https://www.micc.unifi.it/wp-content/uploads/2019/01/1805.11746.pdf
#url_code: '#'
url_dataset: 'https://www.micc.unifi.it/resources/datasets/semantic-road-inpainting/'
#url_poster: 'PosterECCV_2016.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=QjSNRTUGe00&feature=emb_logo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
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
