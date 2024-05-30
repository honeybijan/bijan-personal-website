---
title: "Synthetic Potential Outcomes for Mixtures of Treatment Effects"
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

abstract: "Modern data analysis frequently relies on the use of large datasets, often constructed as amalgamations of diverse populations or data-sources. Heterogeneity across these smaller datasets constitutes two major challenges for causal inference: (1) the source of each sample can introduce latent confounding between treatment and effect, and (2) diverse populations may respond differently to the same treatment, giving rise to heterogeneous treatment effects (HTEs). The issues of latent confounding and HTEs have been studied separately but not in conjunction. In particular, previous works only report the conditional average treatment effect (CATE) among similar individuals (with respect to the measured covariates). CATEs cannot resolve mixtures of potential treatment effects driven by latent heterogeneity, which we call mixtures of treatment effects (MTEs). Inspired by method of moment approaches to mixture models, we propose "synthetic potential outcomes" (SPOs). Our new approach deconfounds heterogeneity while also guaranteeing the identifiability of MTEs. This technique bypasses full recovery of a mixture, which significantly simplifies its requirements for identifiability. We demonstrate the efficacy of SPOs on synthetic data."

# Summary. An optional shortened abstract.
summary: A new technique for causal inference that can sometimes learn more than a randomized controlled trial.

tags: ['mixtures']

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2405.19225'
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
#   Otherwise, set `projects: [![alt text](spos.png)]`.
projects: ['mixtures']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---