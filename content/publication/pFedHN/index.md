---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Personalized Federated Learning using Hypernetworks"
authors: [Aviv Shamsian, Aviv Navon, Ethan Fetaya, Gal Chechik]
date: 2021-05-08T11:09:21-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-08T11:09:21-04:00

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

tags: [Machine Learning, Federated learning, Hypernetworks]
categories: [Machine Learning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2103.04628
url_code: https://github.com/AvivSham/pFedHN
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
Personalized federated learning is tasked with training
machine learning models for multiple clients, each with its own data
distribution. The goal is to train personalized models in a
collaborative way while accounting for data disparities across clients
and reducing communication costs.  We propose a novel approach to this
problem using hypernetworks, termed pFedHN for personalized Federated
HyperNetworks. In this approach, a central hypernetwork model is
trained to generate a set of models, one model for each client. This
architecture provides effective parameter sharing across clients,
while maintaining the capacity to generate unique and diverse personal
models. Furthermore, since hypernetwork parameters are never
transmitted, this approach decouples the communication cost from the
trainable model size. We test pFedHN empirically in several
personalized federated learning challenges and find that it
outperforms previous methods.  Finally, since hypernetworks share
information across clients we show that pFedHN can generalize better
to new clients whose distributions differ from any client observed
during training.

    
### Cite the paper
If you use the contents of this project, please cite our paper.
@article{shamsian2021personalized,
      title={Personalized Federated Learning using Hypernetworks},
      author={Aviv Shamsian and Aviv Navon and Ethan Fetaya and Gal Chechik},
      journal={ICML},
      year={2021}
    }