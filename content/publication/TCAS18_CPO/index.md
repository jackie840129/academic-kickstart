---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Computation-Performance Optimization of Convolutional Neural Networks with Redundant Filter Removal"
authors: ["**Chih-Ting Liu**",Tung-Wei Lin, Yi-Heng Wu, Yu-Sheng Lin, Heng Lee, Yu Tsao, Shao-Yi Chien]
date: 2018-12-27
paper_cat : ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems I: Regular Papers"
publication_short: "IEEE Transactions on Circuits and Systems I: Regular Papers (TCAS-1)"

abstract: "Convolutional neural networks (CNNs) are widely employed in modern computer vision algorithms, where the input image is convolved iteratively by many filters to extract the knowledge behind it. However, while the depth of convolutional layers gets deeper and deeper in recent years, the enormous computational complexity makes it difficult to be deployed on embedded systems with limited hardware resources. In this paper, inspired by rate-distortion optimization in image and video coding, we propose a computation-performance optimization (CPO) method to remove the redundant convolution filters in a CNN with performance constraints. To prove the effectiveness of the proposed method, CPO is applied to the networks for image super-resolution and image classification. Under almost the same PSNR drop and accuracy drop for performance evaluation in these two tasks, we can achieve the best parameter and computation reduction when compared with previous works."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Filter Pruning','Sensitivity']
categories: [Pruning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Bibtex
#  url: https://tsaishien-chen.github.io/publications/SPAN_bibTex.txt
#  icon_pack: fab
#  icon: twitter


url_pdf: iFINAL_VERSIOB.pdf
url_code:
url_dataset:
url_poster: 
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false
  placement : 4

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
