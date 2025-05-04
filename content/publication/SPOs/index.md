---
title: "Synthetic Potential Outcomes and Causal Mixture Identifiability"
authors:
- Admin
- Chandler Squires
- Caroline Uhler
author_notes:
date: "2025-06-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The *28th International Conference on Artificial Intelligence and Statistics (AISTATS)*"
publication_short: "*AISTATS 2025*"

abstract: Heterogeneous data from multiple populations, sub-groups, or sources can be represented as a "mixture model" with a single latent class influencing all of the observed covariates. Heterogeneity can be resolved at different levels by grouping populations according to different notions of similarity. This paper proposes grouping with respect to the causal response of an intervention or perturbation on the system. This is distinct from previous notions, such as grouping by similar covariate values (e.g., clustering) or similar correlations between covariates (e.g., Gaussian mixture models). To solve the problem, we "synthetically sample" from a counterfactual distribution using higher-order multi-linear moments of the observable data. To understand how these ``causal mixtures'' fit in with more classical notions, we develop a hierarchy of mixture identifiability.

# Summary. An optional shortened abstract.
summary: We show how to find mixture components relative to a causal response.

tags:
  -Synthetic Potential Outcomes
  -Mixture Models

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://proceedings.mlr.press/v258/mazaheri25a.html'
url_code: 'https://github.com/csquires/synthetic-potential-outcomes'
url_dataset: ''
url_poster: 'publication/spos/AISTATS2025poster.pdf'
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