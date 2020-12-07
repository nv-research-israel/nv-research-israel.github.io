---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Meta-Sim2: Unsupervised Learning of Scene Structure for Synthetic Data Generation"
authors: [Jeevan Devaranjan*, Amlan Kar*, Sanja Fidler]
date: 2020-09-05T01:33:07-04:00
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-02T01:33:07-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ECCV 2020"
publication_short: "ECCV 2020"

abstract: "Procedural models are being widely used to synthesize scenes for graphics, gaming, and to create (labeled) synthetic datasets for ML. In order to produce realistic and diverse scenes, a number of parameters governing the procedural models have to be carefully tuned by experts. These parameters control both the structure of scenes being generated (e.g. how many cars in the scene), as well as parameters which place objects in valid configurations. Meta-Sim aimed at automatically tuning parameters given a target collection of real images in an unsupervised way. In Meta-Sim2, we aim to learn the scene structure in addition to parameters, which is a challenging problem due to its discrete nature. Meta-Sim2 proceeds by learning to sequentially sample rule expansions from a given probabilistic scene grammar. Due to the discrete nature of the problem, we use Reinforcement Learning to train our model, and design a feature space divergence between our synthesized and target images that is key to successful training. Experiments on a real driving dataset show that, without any supervision, we can successfully learn to generate data that captures discrete structural statistics of objects, such as their frequency, in real images. We also show that this leads to downstream improvement in the performance of an object detector trained on our generated dataset as opposed to other baseline simulation methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [Computer Vision]
categories: [Computer Vision]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2008.09092
#url_code: https://nv-tlabs.github.io/meta-sim-structure/
#url_dataset:
#url_poster:
url_project: https://nv-tlabs.github.io/meta-sim-structure/
#url_slides:
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
