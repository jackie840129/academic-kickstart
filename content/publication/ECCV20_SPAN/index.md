---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Orientation-aware Vehicle Re-identification with Semantics-guided Part Attention Network"
authors: 
- "[Tsai-Shien Chen](https://tsaishien-chen.github.io/)" 
- "**Chih-Ting Liu**"
- Chih-Wei Wu
- Shao-Yi Chien
date: 2020-08-24
paper_cat : "**Oral Paper**"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Computer Vision"
publication_short: "European Conference on Computer Vision (ECCV)"

abstract: "Vehicle re-identification (re-ID) focuses on matching images of the same vehicle across different cameras. It is fundamentally challenging because differences between vehicles are sometimes subtle. While several studies incorporate spatial-attention mechanisms to help vehicle re-ID, they often require expensive keypoint labels or suffer from noisy attention mask if not trained with expensive labels. In this work, we propose a dedicated Semantics-guided Part Attention Network (SPAN) to robustly predict part attention masks for different views of vehicles given only image-level semantic labels during training. With the help of part attention masks, we can extract discriminative features in each part separately. Then we introduce Co-occurrence Part-attentive Distance Metric (CPDM) which places greater emphasis on co-occurrence vehicle parts when evaluating the feature distance of two images. Extensive experiments validate the effectiveness of the proposed method and show that our framework outperforms the state-of-the-art approaches."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Vehicle Re-Identification','visibility-aware features','semantic-guided learning']
categories: [Re-ID]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
#links:
#- name: Bibtex
#  url: https://tsaishien-chen.github.io/publications/SPAN_bibTex.txt
#  icon_pack: fab
#  icon: twitter


url_pdf: http://media.ee.ntu.edu.tw/research/SPAN/papers/ECCV20_VehicleReID.pdf
url_code: https://github.com/tsaishien-chen/SPAN
url_dataset:
url_poster:
url_project: http://media.ee.ntu.edu.tw/research/SPAN/
url_slides: https://tsaishien-chen.github.io/publications/SPAN_slides.pdf
url_source:
url_video: https://www.youtube.com/watch?v=gHBnue6U1Ec&feature=youtu.be

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

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
