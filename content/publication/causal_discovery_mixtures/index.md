---
title: "Discrete Nonparametric Causal Discovery under Latent Class Confounding"
authors:
- Admin
- Spencer Gordon
- Yuval Rabani
- Leonard Schulman
author_notes:
date: "2023-11-14T00:00:00Z"
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

abstract: Directed acyclic graphs are used to model the causal structure of a system. ``Causal discovery'' describes the problem of learning this structure from data. When data is an aggregate from multiple sources (populations or environments), global confounding obscures conditional independence properties that drive many causal discovery algorithms. For this reason, existing causal discovery algorithms are not suitable for the multiple-source setting. We demonstrate that, if the confounding is of bounded cardinality (i.e. the data comes from a limited number of sources), causal discovery can still be achieved. The feasibility of this problem is governed by a trade-off between the cardinality of the global confounder, the cardinalities of the observed variables, and the sparsity of the causal structure.
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