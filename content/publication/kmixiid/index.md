---
title: "The Sparse Hausdorff Moment Problem, with Application to Topic Models"
authors:
  - Spencer Gordon
  - admin
  - Yuval Rabani
  - Leonard Schulman

# Author notes (optional)
author_notes:
  - 
  - 'Author order is alphabetical'
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'We consider the problem of identifying, from its first m noisy moments, a probability distribution on $[0,1]$ of support $k<\infty$. This is equivalent to the problem of learning a distribution on m observable binary random variables $X_1,X_2,\ldots,X_m$ that are iid conditional on a hidden random variable $U$ taking values in $\{1,2,\ldots,k\}$. Our focus is on accomplishing this with $m=2k$, which is the minimum $m$ for which verifying that the source is a $k$-mixture is possible (even with exact statistics). This problem, so simply stated, is quite useful: e.g., by a known reduction, any algorithm for it lifts to an algorithm for learning pure topic models.<br> <br> We give an algorithm for identifying a $k$-mixture using samples of $m=2k$ iid binary random variables using a sample of size $(1/w_{\min})2 \cdot (1/\zeta)\mathcal{O}(k)$ and post-sampling runtime of only $\mathcal{O}(k^2+o(1))$ arithmetic operations. Here $w_\min$ is the minimum probability of an outcome of $U$, and $\zeta$ is the minimum separation between the distinct success probabilities of the $X_i$s. Stated in terms of the moment problem, it suffices to know the moments to additive accuracy $w_{\min} \cdot \zeta \mathcal{O}(k)$. It is known that the sample complexity of any solution to the identification problem must be at least exponential in $k$. Previous results demonstrated either worse sample complexity and worse $\mathcal{O}(kc)$ runtime for some $c$ substantially larger than 2, or similar sample complexity and much worse $k \mathcal{O}(k^2)$ runtime.'

# Summary. An optional shortened abstract.
summary: We use Prony's method to solve the $k$-MixIID problem, which gives improved sample and time complexity via a new stability analysis.

tags:
- Discrete Mixture Models
featured: false

links:
url_pdf: https://arxiv.org/pdf/2007.08101.pdf
url_source: #https://arxiv.org/abs/2007.08101

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- mixtures

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
