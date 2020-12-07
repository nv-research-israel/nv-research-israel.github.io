---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lift, Splat, Shoot: Encoding Images from Arbitrary Camera Rigs by Implicitly Unprojecting to 3D"
authors: [Jonah Philion, Sanja Fidler]
date: 2020-09-04T01:33:07-04:00
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-03T01:33:07-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ECCV 2020"
publication_short: "ECCV 2020"

abstract: "The goal of perception for autonomous vehicles is to extract semantic representations from multiple sensors and fuse these representations into a single 'bird's-eye-view' coordinate frame for consumption by motion planning. We propose a new end-to-end architecture that directly extracts a bird's-eye-view representation of a scene given image data from an arbitrary number of cameras. The core idea behind our approach is to 'lift' each image individually into a frustum of features for each camera, then 'splat' all frustums into a rasterized bird's-eye-view grid. By training on the entire camera rig, we provide evidence that our model is able to learn not only how to represent images but how to fuse predictions from all cameras into a single cohesive representation of the scene while being robust to calibration error. On standard bird's-eye-view tasks such as object segmentation and map segmentation, our model outperforms all baselines and prior work. In pursuit of the goal of learning dense representations for motion planning, we show that the representations inferred by our model enable interpretable end-to-end motion planning by 'shooting' template trajectories into a bird's-eye-view cost map output by our network. We benchmark our approach against models that use oracle depth from lidar."

# Summary. An optional shortened abstract.
summary: ""

tags: [Computer Vision]
categories: [Computer Vision]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2008.05711
url_code: https://github.com/nv-tlabs/lift-splat-shoot
#url_dataset:
#url_poster:
url_project: https://nv-tlabs.github.io/lift-splat-shoot/
#url_slides:
#url_source:
url_video: https://www.youtube.com/watch?v=ypQQUG4nFJY

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