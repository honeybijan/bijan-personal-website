---
title: Distribution Shift and Transportability
summary: 'Statistical prediction models are often trained on data that is drawn from different probability distributions than their eventual use cases. My (upcomming) work uses insights from causal inference to develop new methods for building machine learning models that are robust to environmental changes.'
date: '2016-04-27T00:00:00Z'
weight: 1
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

The principle assumption when building any (not necessarily causal) prediction model is access to relevant data for the
task at hand. When predicting label $Y$ from inputs $\mathbf{X}$, this
assumption reads that the data is drawn from a (training)
probability distribution $\mathbf{X}, Y$ that is identical to the distribution that will generate its use-cases (target distribution). 

Unfortunately, the dynamic nature of real-world systems
makes obtaining perfectly relevant data difficult. Datagathering mechanisms can introduce sampling bias, yielding
distorted training data. Even in the absence of sampling biases, populations, environments, and interventions give rise
to distribution shifts in their own right.

This issue is fundimentally related to causality: causal relationships are more likely to hold up in new environments than correlational ones. In the past, I have worked on new methods for reweighting data for domain adaptation. Currently, I am interested in developing frameworks to understand distribution shift from a causal perspective, especially in the presence of unobserved concepts (which can span both causes and effects).