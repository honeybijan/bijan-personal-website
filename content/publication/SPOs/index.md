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

abstract: A mixture model consists of a latent class that exerts a discrete signal on the observed data. Uncovering these latent classes is fundamental to unsupervised learning. In this paper, we consider the problem of recovering latent classes defined with respect to causal responses. We allow overlapping support in the distributions of these classes, meaning individuals cannot be clustered into groups with a similar response. Instead, we build on a setting from proximal causal inference to develop a method of moments approach to synthetically sample potential outcome distributions. This approach is the first known identifiability result for what we call Mixtures of Treatment Effects (MTEs). More broadly, we show how MTEs fit into a hierarchy of causal identifiability that unifies a number of perspectives on latent class confounding.

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
url_slides: 'presentations/SPO_BU'
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