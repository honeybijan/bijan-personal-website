---
title: "Identification of Mixtures of Discrete Product Distributions in Near-Optimal Sample and Time Complexity"
authors:
- Spencer Gordon
- Eric Jahn
- Admin
- Yuval Rabani
- Leonard Schulman
# Author notes (optional)
author_notes:
  - 
  -
  - 'Author order is alphabetical'

date: "2023-09-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We consider the problem of *identifying*, from statistics, a distribution of discrete random variables $X_1,\ldots,X_n$ that is a mixture of $k$ product distributions. The best previous sample complexity for $n \in O(k)$ was $(1/\zeta)^{O(k^2 \log k)}$ (under a mild separation assumption parameterized by $\zeta$). The best known lower bound was $\exp(\Omega(k))$. It is known that $n\geq 2k-1$ is necessary and sufficient for identification. We show, for any $n\geq 2k-1$, how to achieve sample complexity and run-time complexity $(1/\zeta)^{O(k)}$. We also extend the known lower bound of $e^{\Omega(k)}$ to match our upper bound across a broad range of $\zeta$. Our results are obtained by combining (a) a classic method for robust tensor decomposition, (b) a novel way of bounding the condition number of key matrices called Hadamard extensions, by studying their action only on flattened rank-1 tensors.

# Summary. An optional shortened abstract.
summary: A (near) resolution of the sample complexity gap for mixtures of products.

tags:
  -Mixture Models

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2309.13993'
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