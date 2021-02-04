---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Auxiliary Learning by Implicit Differentiation"
authors: [Aviv Navon, Idan Achituve, Haggai Maron, Gal Chechik, Ethan Fetaya]
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
publication: "International Conference on Learning Representations"
publication_short: "ICLR 2021"

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

url_pdf: https://arxiv.org/abs/2007.02693
url_code: https://github.com/AvivNavon/AuxiLearn
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
Training with multiple auxiliary tasks is a common practice used in deep learning for improving the performance on the main task of interest. Two main challenges arise in this multi-task learning setting: (i) Designing useful auxiliary tasks; and (ii) Combining auxiliary tasks into a single coherent loss. We propose a novel framework, AuxiLearn, that targets both challenges, based on implicit differentiation. First, when useful auxiliaries are known, we propose learning a network that combines all losses into a single coherent objective function. This network can learn non-linear interactions between auxiliary tasks. Second, when no useful auxiliary task is known, we describe how to learn a network that generates a meaningful, novel auxiliary task. We evaluate AuxiLearn in a series of tasks and domains, including image segmentation and learning with attributes. We find that AuxiLearn consistently improves accuracy compared with competing methods.
    
### Cite the paper
If you use the contents of this project, please cite our paper.
@article{navon2020auxiliary,
      title={Auxiliary Learning by Implicit Differentiation},
      author={Navon, Aviv and Achituve, Idan and Maron, Haggai and Chechik, Gal and Fetaya, Ethan},
      journal={arXiv preprint arXiv:2007.02693},
      year={2020}
    }