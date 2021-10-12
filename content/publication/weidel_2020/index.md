---
title: "Unsupervised learning and clustered connectivity enhance reinforcement learning in spiking neural networks"
authors:
- Philipp Weidel
- admin
- Abigail Morrison
date: "2020-03-17T00:00:00Z"
doi: "10.1101/2020.03.17.995563"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: Reinforcement learning is a learning paradigm that can account for how organisms learn to adapt their behavior in complex environments with sparse rewards. However, implementations in spiking neuronal networks typically rely on input architectures involving place cells or receptive fields. This is problematic, as such approaches either scale badly as the environment grows in size or complexity, or presuppose knowledge on how the environment should be partitioned. Here, we propose a learning architecture that combines unsupervised learning on the input projections with clustered connectivity within the representation layer. This combination allows input features to be mapped to clusters; thus the network self-organizes to produce task-relevant activity patterns that can serve as the basis for reinforcement learning on the output projections. On the basis of the MNIST and Mountain Car tasks, we show that our proposed model performs better than either a comparable unclustered network or a clustered network with static input projections. We conclude that the combination of unsupervised learning and clustered connectivity provides a generic representational substrate suitable for further computation.

# Summary. An optional shortened abstract.
summary: ""
 

tags:
- Connectivity
- Learning
- Clusters
- Processing

featured: true

links:
- icon: biorxiv
  icon_pack: ai
  name: Preprint
  url: https://www.biorxiv.org/content/10.1101/2020.03.17.995563v1.full
- icon: file-pdf
  icon_pack: fa
  name: PDF
  url: https://www.biorxiv.org/content/10.1101/2020.03.17.995563v1.full.pdf
- icon: impactstory
  icon_pack: ai
  name: Impact
  url: https://www.biorxiv.org/content/10.1101/2020.03.17.995563v1.article-metrics

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 1
  caption: ''
  focal_point: "Smart"
  preview_only: true

header:
  image: "featured.jpg"
  caption: ""

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

