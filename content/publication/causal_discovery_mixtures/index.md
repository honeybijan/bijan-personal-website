---
title: "Causal Discovery under Latent Class Confounding"
authors:
- Admin
- Spencer Gordon
- Yuval Rabani
- Leonard Schulman
author_notes:
date: "2025-03-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: An acyclic causal structure can be described with directed acyclic graph (DAG), where arrows indicate the possibility of direct causation. The task of learning this structure from data is known as "causal discovery." Diverse populations or changing environments can sometimes give rise to data that is heterogeneous in the sense that each population/environment is a "source" which idiosyncratically determines the forms of those direct causal effects. From this perspective, the source is a latent common cause for every observed variable. While some methods for causal discovery are able to work around latent confounding in special cases, especially when only few observables are confounded, a global confounder is a difficult challenge. The only known ways to deal with latent global confounding involve assumptions that limit the structural equations and/or noise functions. We demonstrate that globally confounded causal structures can still be identifiable with arbitrary structural equations and noise functions, so long as the number of latent classes remains small relative to the size and sparsity of the underlying DAG.
# Summary. An optional shortened abstract.
summary: The first known algorithm for causal discovery under latent class counfounding.

tags:
  -Causal Discovery
  -Mixture Models

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2311.07454'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point:
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['mixtures']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---