---
title: Time-Dependent Genomic Signatures for Cancer Classification and Prediction 
summary: 'We process non-coding regions of the genome which contain duplication and mutation signatures. These **mutation profiles** have been shown to be predictive of various forms of cancer.'
date: '2018-01-01T00:00:00Z'
weight: 4
profile: false

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We consider two forms of mutations in the genome:
1. **Duplication**: The formation of adjacent copies of a substring, usually caused by "slipping" during the replication phase. <br>For example: $T\underline{CG}A \rightarrow T\underline{CGCG}A$
2. **Point Mutation**: The change of a single base pair. <br>For example: $T\underline{C}GA \rightarrow T\underline{G}GA$.

The genome contains non-coding regions called "repeat regions" with significant duplication activity. When point mutations occur in these regions, those errors are propagated through further duplications. Hence, it is possible to partially construct a duplication and point mutation history of the genome using a single snapshot of these repeat regions. Such a history gives insight into the relative rates of duplication and point mutation for specific locations on the genome. We call this history a **mutation profile** for which we have a patent. We have demonstrated that cancer patients have unique mutation profiles in their non-tumorous DNA, seemingly predicting their propensity for specific types of cancer.