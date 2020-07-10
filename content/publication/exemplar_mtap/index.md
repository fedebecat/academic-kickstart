---
title: "Indexing quantized ensembles of exemplar-SVMs with rejecting taxonomies"
authors:
- admin
- Lorenzo Seidenari
- Alberto Del Bimbo
date: "2017-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Multimedia Tools and Applications*
publication_short: In *mtap*

abstract: Ensembles of Exemplar-SVMs have been introduced as a framework for Object Detection but have rapidly found a large interest in a wide variety of computer vision applications such as mid-level feature learning, tracking and segmentation. What makes this technique so attractive is the possibility of associating to instance specific classifiers one or more semantic labels that can be transferred at test time. To guarantee its effectiveness though, a large collection of classifiers has to be used. This directly translates in a high computational footprint, which could make the evaluation step prohibitive. To overcome this issue we organize Exemplar-SVMs into a taxonomy, exploiting the joint distribution of Exemplar scores. This permits to index the classifiers at a logarithmic cost, while maintaining the label transfer capabilities of the method almost unaffected. We propose different formulations of the taxonomy in order to maximize the speed gain. In particular we propose a highly efficient Vector Quantized Rejecting Taxonomy to discard unpromising image regions during evaluation, performing computations in a quantized domain. This allow us to obtain ramarkable speed gains, with an improvement up to more than two orders of magnitude. To verify the robustness of our indexing data structure with reference to a standard Exemplar-SVM ensemble, we experiment with the Pascal VOC 2007 benchmark on the Object Detection competition and on a simple segmentation task.

# Summary. An optional shortened abstract.
summary: Accelerated ensemble of Exemplar-SVMs for object detection using rejecting taxonomies and quantized templates.

tags:
- Exemplar-SVM
- Object Detection
- Label Transfer
- Taxonomy Learning
- Vector Quantization
featured: false

links:
#- name: Arxiv
#  url: https://arxiv.org/abs/1609.00221
url_pdf: https://www.micc.unifi.it/wp-content/uploads/2018/01/fca5c80995369061e9c302f9cc9e82d0d883.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: 'PosterECCV_2016.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'https://vimeo.com/215859472'

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

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
