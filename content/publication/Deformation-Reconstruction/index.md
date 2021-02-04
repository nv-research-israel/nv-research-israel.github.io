---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Self-Supervised Learning for Domain Adaptation on Point-Clouds"
authors: [Idan Achituve, Haggai Maron, Gal Chechik]
date: 2020-12-30T11:09:21-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-30T11:09:21-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Winter Conference on Applications of Computer Vision"
publication_short: "WACV 2021"

abstract: 

# Summary. An optional shortened abstract.
summary: ""

tags: [Machine Learning, Optimization, Multi-task learning]
categories: [Machine Learning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2003.12641
url_code: https://github.com/IdanAchituve/DefRec_and_PCM
url_dataset: 
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=owpoM1Mv1jE

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
 caption: ""
 focal_point: ""
 preview_only: true

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

### Video

### Abstract
Self-supervised learning (SSL) is a technique for learning useful representations from unlabeled data. It has been applied effectively to domain adaptation (DA) on images and videos. It is still unknown if and how it can be leveraged for domain adaptation in 3D perception problems. Here we describe the first study of SSL for DA on point clouds. We introduce a new family of pretext tasks, Deformation Reconstruction, inspired by the deformations encountered in sim-to-real transformations. In addition, we propose a novel training procedure for labeled point cloud data motivated by the MixUp method called Point cloud Mixup (PCM). Evaluations on domain adaptations datasets for classification and segmentation, demonstrate a large improvement over existing and baseline methods.

### Cite the paper
If you use the contents of this project, please cite our paper.@inproceedings{achituve2021self,
  title={Self-Supervised Learning for Domain Adaptation on Point Clouds},
  author={Achituve, Idan and Maron, Haggai and Chechik, Gal},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={123--133},
  year={2021}
}