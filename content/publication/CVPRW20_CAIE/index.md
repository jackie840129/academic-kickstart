---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Constraint-Aware Importance Estimation for Global Filter Pruning Under Multiple Resource Constraints"
authors: [Yu-Cheng Wu, "**Chih-Ting Liu**", Bo-Ying Chen, Shao-Yi Chien]
date: 2020-06-13
paper_cat : "Spotlight Paper"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops & Joint Workshop on Efficient Deep Learning in Computer Vision"
publication_short: "IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)"

abstract: "Filter pruning is an efficient way to structurally remove the redundant parameters in convolutional neural network, where at the same time reduces the computation, memory storage and transfer cost. Recent state-of-the-art methods globally estimate the importance of each filter based on its impact to the loss and iteratively remove those with smaller values until the pruned network meets some resource constraints, such as the commonly used number (or ratio) of filter left. However, when there is a more practical constraint like the total number of FLOPs, they ignore its relation to the estimation of filter importance. We propose a novel method called Constraint-Aware Importance Estimation (CAIE) that integrates information of the impact on the given resource into the original importance estimation only based on loss when pruning each filter. Moreover, our CAIE can be generalized to the pruning problem under multiple resource constraints simultaneously. Extensive experiments show that under the same multiple resource constraints, the model pruned with our CAIE method can not only accurately meet the constraints but also achieve the optimal performance results when comparing to existing state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Importance Estimation','Multiple Resource Constriants','Filter Pruning']
categories: [Pruning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Bibtex
#  url: https://tsaishien-chen.github.io/publications/SPAN_bibTex.txt
#  icon_pack: fab
#  icon: twitter


url_pdf: https://openaccess.thecvf.com/content_CVPRW_2020/papers/w40/Wu_Constraint-Aware_Importance_Estimation_for_Global_Filter_Pruning_Under_Multiple_Resource_CVPRW_2020_paper.pdf
url_code: https://github.com/mediaic/CAIE-Filter-Pruning
url_dataset:
url_poster: 
url_project:
url_slides: 13-slides.pdf
url_source:
url_video: 13.mp4

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
