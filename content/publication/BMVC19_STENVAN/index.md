---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Spatially and Temporally Efficient Non-local Attention Network for Video-based Person Re-Identification"
authors: 
- "**Chih-Ting Liu**"
- Chih-Wei Wu
- "[Yu-Chiang Frank Wang](https://www.ee.ntu.edu.tw/profile1.php?teacher_id=24037)"
- Shao-Yi Chien
date: 2019-09-01
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
publication: "British Machine Vision Conference"
publication_short: "British Machine Vision Conference (BMVC)"

abstract: "Video-based person re-identification (Re-ID) aims at matching video sequences of pedestrians across non-overlapping cameras. It is a practical yet challenging task of how to embed spatial and temporal information of a video into its feature representation. While most existing methods learn the video characteristics by aggregating image-wise features and designing attention mechanisms in Neural Networks, they only explore the correlation between frames at high-level features. In this work, we target at refining the intermediate features as well as high-level features with non-local attention operations and make two contributions.(i) We propose a Non-local Video Attention Network (NVAN) to incorporate video characteristics into the representation at multiple feature levels.(ii) We further introduce a Spatially and Temporally Efficient Non-local Video Attention Network (STE-NVAN) to reduce the computation complexity by exploring spatial and temporal redundancy presented in pedestrian videos. Extensive experiments show that our NVAN outperforms state-of-the-arts by 3.8% in rank-1 accuracy on MARS dataset and confirms our STE-NVAN displays a much superior computation footprint compared to existing methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Video-based Re-Identification','Non-local Attention','Performance-Computation Trade-off']
categories: [Re-ID]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Bibtex
#  url: https://tsaishien-chen.github.io/publications/SPAN_bibTex.txt
#  icon_pack: fab
#  icon: twitter


url_pdf: http://media.ee.ntu.edu.tw/research/STE_NVAN/BMVC19_STE_NVAN_cam.pdf
url_code: https://github.com/jackie840129/STE-NVAN
url_dataset:
url_poster: http://media.ee.ntu.edu.tw/research/STE_NVAN/BMVC19_ChihTing_final.pdf
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
