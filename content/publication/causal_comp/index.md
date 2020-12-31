---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A causal view of compositional zero-shot recognition"
authors: [Yuval Atzmon, Felix Kreuk, Uri Shalit, Gal Chechik]
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
publication: "NeurIPS 2020 (Spotlight)"
publication_short: "NeurIPS 2020"

abstract: 

# Summary. An optional shortened abstract.
summary: ""

tags: [Computer Vision, Machine Learning]
categories: [Machine Learning]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2006.14610
url_code: https://github.com/nv-research-israel/causal_comp
url_dataset: https://github.com/nv-research-israel/causal_comp
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=IUAmwBylvyc

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

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

<iframe width="700" height="410" src="https://www.youtube.com/embed/IUAmwBylvyc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Abstract
People easily recognize new visual categories that are new combinations of known components. This compositional generalization capacity is critical for learning in real-world domains like vision and language because the long tail of new combinations dominates the distribution. Unfortunately, learning systems struggle with compositional generalization because they often build on features that are correlated with class labels even if they are not "essential" for the class. This leads to consistent misclassification of samples from a new distribution, like new combinations of known components.
    Here we describe an approach for compositional generalization that builds on causal ideas. First, we describe compositional zero-shot learning from a causal perspective, and propose to view zero-shot inference as finding - which intervention caused the observed image?. Second, we present a causal-inspired embedding model that learns disentangled representations of elementary components of visual objects from correlated (confounded) training data. We evaluate this approach on two datasets for predicting new combinations of attribute-object pairs: A well-controlled synthesized images dataset and a real-world dataset which consists of fine-grained types of shoes. We show improvements compared to strong baselines.
    
### Cite the paper
If you use the contents of this project, please cite our paper.

    @inproceedings{neurips2020_causal_comp_atzmon,
     author = {Atzmon, Yuval and Kreuk, Felix and Shalit, Uri and Chechik, Gal},
     booktitle = {Advances in Neural Information Processing Systems},
     title = {A causal view of compositional zero-shot recognition},
     year = {2020}
    }
