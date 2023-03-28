---
title: "Towards reproducible models of sequence learning: replication and analysis of a modular spiking network with reward-based learning"
authors:
- Barna Zajzon
- Renato Duarte
- Abigail Morrison
date: "2023-01-18T00:00:00Z"
doi: "10.1101/2023.01.18.524604"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "BioRxiv"
publication_short: ""

abstract: To acquire statistical regularities from the world, the brain must reliably process, and learn from, spatiotemporally structured information. Although an increasing number of computational models have attempted to explain how such sequence learning may be implemented in the neural hardware, many remain limited in functionality or lack biophysical plausibility. If we are to harvest the knowledge within these models and arrive at a deeper mechanistic understanding of sequential processing in cortical circuits, it is critical that the models and their findings are accessible, reproducible, and quantitatively comparable. Here we illustrate the importance of these aspects by providing a thorough investigation of a recent model proposed by Cone and Shouval (2021). We re-implement the modular columnar architecture and reward-based learning rule in the open-source NEST simulator, and successfully replicate the main findings of the original study. Building on these, we perform an in-depth analysis of the model’s robustness to parameter settings and underlying assumptions, highlighting its strengths and weaknesses. We demonstrate a limitation of the model consisting in the hard-wiring of the sequence order in the connectivity patterns, and suggest possible solutions. Finally, we show that the core functionality of the model is retained under more biologically-plausible constraints.


# Summary. An optional shortened abstract.
summary: ""

tags:
- Sequence
- Cortex
- Learning
- Processing

featured: false

links:
- icon: file-pdf
  icon_pack: fa
  name: PDF
  url: https://www.biorxiv.org/content/10.1101/2023.01.18.524604v1.full.pdf
- icon: biorxiv
  icon_pack: ai
  name: Preprint
  url: https://www.biorxiv.org/content/10.1101/2023.01.18.524604v1
- icon: github
  icon_pack: fab
  name: Code & Data
  url: https://github.com/zbarni/re_modular_seqlearn
- icon: impactstory
  icon_pack: ai
  name: Impact
  url: https://www.biorxiv.org/content/10.1101/2023.01.18.524604v1.article-metrics


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 1
  caption: ''
  focal_point: "Smart"
  preview_only: true

header:
  image: ""
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
