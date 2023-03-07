---
title: "Cancer Classification from Healthy DNA"
authors:
  - Siddharth Jain
  - admin
  - Netanel Raviv
  - Jehoshua Bruck

# Author notes (optional)
author_notes:
date: "2020-04-20T00:00:00Z"
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

abstract: 'The genome is traditionally viewed as a *time-independent* source of information; a paradigm that drives researchers to seek correlations between the presence of certain genes and a patient’s risk of disease. This analysis neglects *genomic temporal changes*, which we believe to be a crucial signal for predicting an individual’s susceptibility to cancer. We hypothesize that each individual’s genome passes through an **evolution channel** (The term *channel* is motivated by the notion of communication channel introduced by Shannon1 in 1948 and started the area of *Information Theory*), that is controlled by hereditary, environmental and stochastic factors. This channel differs among individuals, giving rise to varying predispositions to developing cancer. We introduce the concept of **mutation profiles** that are computed without any comparative analysis, but by analyzing the short tandem repeat regions in a *single healthy genome* and capturing information about the individual’s evolution channel. Using machine learning on data from more than 5,000 TCGA cancer patients, we demonstrate that these mutation profiles can accurately distinguish between patients with various types of cancer. For example, the pairwise validation accuracy of the classifier between PAAD (pancreas) patients and GBM (brain) patients is 93%. Our results show that healthy unaffected cells still contain a cancer-specific signal, which opens the possibility of cancer prediction from a healthy genome.'

# Summary. An optional shortened abstract.
summary: We introduce mutation profiles as a way to capture time-dependent information in the repeat region of a genome and demonstrate the ability of mutation profiles to predict cancer-type from non-tumor DNA.

tags:
- Cancer
featured: false

links:
url_pdf: https://www.biorxiv.org/content/10.1101/517839v2.full.pdf
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
- cancer

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
