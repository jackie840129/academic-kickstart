---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Computation-Performance Optimization of Convolutional Neural Networks with Redundant Kernel Removal"
authors: ["**Chih-Ting Liu**",Yi-Heng Wu, Yu-Sheng Lin, Shao-Yi Chien]
date: 2018-05-27
paper_cat : ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Symposium on Circuits and Systems"
publication_short: "IEEE International Symposium on Circuits and Systems (ISCAS)"

abstract: "Deep Convolutional Neural Networks (CNNs) are
widely employed in modern computer vision algorithms, where
the input image is convolved iteratively by many kernels to
extract the knowledge behind it. However, with the depth of
convolutional layers getting deeper and deeper in recent years,
the enormous computational complexity makes it difficult to be
deployed on embedded systems with limited hardware resources.
In this paper, we propose two computation-performance optimization methods to reduce the redundant convolution kernels
of a CNN with performance and architecture constraints, and
apply it to a network for super resolution (SR). Using PSNR
drop compared to the original network as the performance
criterion, our method can get the optimal PSNR under a certain
computation budget constraint. On the other hand, our method
is also capable of minimizing the computation required under a
given PSNR drop."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Filter Pruning','Kernel Sparsity','Performance-Computation Trade-off']
categories: [Pruning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Bibtex
#  url: https://tsaishien-chen.github.io/publications/SPAN_bibTex.txt
#  icon_pack: fab
#  icon: twitter


url_pdf: https://arxiv.org/pdf/1705.10748.pdf 
url_code: 
url_dataset:
url_poster: 
url_project:
url_slides: ISCAS_CPO.pdf
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
