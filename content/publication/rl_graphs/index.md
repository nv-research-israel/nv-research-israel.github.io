---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How to Stop Epidemics: Controlling Graph Dynamics with Reinforcement Learning and Graph Neural Networks"
authors: [Eli A. Meirom, Haggai Maron, Shie Mannor, Gal Chechik]
date: 2021-05-11T11:09:21-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-11T11:09:21-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning 2021"
publication_short: "ICML 2021"

abstract: "We consider the problem of monitoring and controlling a partially-observed dynamic process that spreads over a graph. This problem naturally arises in contexts such as scheduling virus tests or quarantining individuals to curb a spreading epidemic; detecting fake news spreading on online networks by manually inspecting posted articles; and targeted marketing where the objective is to encourage the spread of a product. Curbing the spread and constraining the fraction of infected population becomes challenging when only a fraction of the population can be tested or quarantined.
To address this challenge, we formulate this setup as a sequential decision problem over a graph. In face of an exponential state space, combinatorial action space and partial observability, we design RLGN, a novel tractable Reinforcement Learning (RL) scheme to prioritize which nodes should be tested, using Graph Neural Networks (GNNs) to rank the graph nodes. We evaluate this approach in three types of social-networks: community-structured, preferential attachment, and based on statistics from real cellular tracking. RLGN consistently outperforms all baselines in our experiments. It suggests that prioritizing tests using RL on temporal graphs can increase the number of healthy people by 25% and contain the epidemic 30% more often than supervised approaches and 2.5× more often than non-learned baselines using the same resources."

# Summary. An optional shortened abstract.
summary: ""

tags: [Reinfocement Learning, Machine Learning, Graph Neural Networks]
categories: [Machine Learning]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2010.05313.pdf
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
