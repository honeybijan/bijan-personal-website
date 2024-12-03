---
title: "Synthetic Potential Outcomes and Causal Mixture Identifiability"
authors:
- Admin
- Chandler Squires
- Caroline Uhler
author_notes:
date: "2024-05-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Heterogeneous data from multiple populations, sub-groups, or sources is often represented as a "mixture model” with a single latent class influencing all of the observed covariates. Heterogeneity can be resolved at multiple levels by grouping populations according to different notions of similarity. This paper proposes grouping with respect to the causal response of an intervention or perturbation on the system. This definition is distinct from previous notions, such as similar covariate values (e.g. clustering) or similar correlations between covariates (e.g. Gaussian mixture models). To solve the problem, we “synthetically sample” from a counterfactual distribution using higher-order multi-linear moments of the observable data. To understand how these "causal mixtures" fit in with more classical notions, we develop a hierarchy of mixture identifiability.

# Summary. An optional shortened abstract.
summary: A new technique for causal inference that can sometimes learn more than a randomized controlled trial.

tags:
  -Synthetic Potential Outcomes
  -Mixture Models

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2405.19225'
url_code: 'https://github.com/csquires/synthetic-potential-outcomes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'presentations/spo_bu3'
url_source: ''
url_video: 'https://www.youtube.com/watch?app=desktop&si=rckWo1PphQC5QqoC&v=hLr7KmUUvJ4&feature=youtu.be'

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
#   Otherwise, set `projects: [![alt text](spos.png)]`.
projects: ['mixtures']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---