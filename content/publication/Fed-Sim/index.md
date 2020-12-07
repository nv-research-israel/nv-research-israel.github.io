---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Federated Simulation or Medical Imaging"
authors: [Daiqing Li, Amlan Kar, Nishant Ravikumar, Alejandro Frangi, Sanja Fidler]
date: 2020-10-01T10:58:41-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-01T10:58:41-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "MICCAI 2020"
publication_short: "MICCAI 2020 (Nominated for the Young Scientist Award)"

abstract: "Labelling data is expensive and time consuming especially for domains such as medical imaging that contain volumetric imaging data and require expert knowledge. Exploiting a larger pool of labeled data available across multiple centers, such as in federated learning, has also seen limited success since current deep learning approaches do not generalize well to images acquired with scanners from different manufacturers. We aim to address these problems in a common, learning-based image simulation framework which we refer to as Federated Simulation. We introduce a physics-driven generative approach that consists of two learnable neural modules: 1) a module that synthesizes 3D cardiac shapes along with their materials, and 2) a CT simulator that renders these into realistic 3D CT Volumes, with annotations. Since the model of geometry and material is disentangled from the imaging sensor, it can effectively be trained across multiple medical centers. We show that our data synthesis framework improves the downstream segmentation performance on several datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: [Medical Imaging]
categories: [Medical Imaging]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2009.00668
#url_code:
#url_dataset:
#url_poster:
url_project: https://nv-tlabs.github.io/fed-sim/
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
