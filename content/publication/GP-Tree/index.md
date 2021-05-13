---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GP-Tree: A Gaussian Process Classifier for Few-Shot Incremental Learning"
authors: [Idan Achituve, Aviv Navon, Yochai Yemini, Gal Chechik, Ethan Fetaya]
date: 2021-05-09T11:09:21-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-09T11:09:21-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning"
publication_short: "ICML 2021"

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

url_pdf: https://arxiv.org/abs/2102.07868
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
Gaussian processes (GPs) are non-parametric, flexible, models that
work well in many tasks.  Combining GPs with deep learning methods via
deep kernel learning is especially compelling due to the strong
expressive power induced by the network. However, inference in GPs,
whether with or without deep kernel learning, can be computationally
challenging on large datasets. Here, we propose GP-Tree, a novel
method for multi-class classification with Gaussian processes and deep
kernel learning. We develop a tree-based hierarchical model in which
each internal node of the tree fits a GP to the data using the
Polya-Gamma augmentation scheme. As a result, our method scales well
with both the number of classes and data size. We demonstrate our
method effectiveness against other Gaussian process training
baselines, and we show how our general GP approach is easily applied
to incremental few-shot learning and reaches state-of-the-art
performance.
    
### Cite the paper
If you use the contents of this project, please cite our paper.
@article{achituve2021gptree,
      title={GP-Tree: A Gaussian Process Classifier for Few-Shot Incremental Learning},
      author={Achituve, Idan and Navon, Aviv and Yemini, Yochai andChechik, Gal and Fetaya, Ethan},
      journal={ICML 2021},
      year={2021}
    }
