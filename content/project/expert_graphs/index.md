---
title: Decision Fusion
summary: ' It is not unusual for studies and experts to disagree with each other. Such disagreement is often driven by differing contexts rather than incorrect deductions or bad data. One way to investigate contradiction is to use merged data to build a larger picture. Unfortunately, many private medical settings deny direct access to data. Through decision fusion, I seek to understand when results from different settings are in conflict and what these disagreements can indicate about the underlying system.'
date: '2016-04-27T00:00:00Z'
weight: 2
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

Imagine you have a cough with three possible explanations: COVID, allergies, or Cancer. You can visit the following specialists with overlapping expertise:
1. General Practitioner: An expert on destinguishing diseasses like COVID from allergies.
2. Oncologist: An expert on diagnosing lung cancer, but has seen a lot of COVID cases mistakenly come through recently.
3. Expert on Environmental Exposure: An expert on lung diseases caused by environmental exposure, from lung cancer from asbestos and allergies from pollen.

Each of these experts is capable of accurately determining the difference between only *two* of the three options. The goal of high level data fusion is to synthesize these opinions. From a machine learning perspective, these experts are prediction models trained on data biased to subsets of the labels.

In voting theory, the **Condorcet Paradox** arises on convex combinations of ranked choices - leading to "cycles of preference" amoung pairwise elections (i.e. A beats B beats C beats A). Fascinatingly, this same paradox emerges in the context of the networks of experts we have just described. Furthermore, the properties of preference that emerge in ranked choice voting systems, known as the **Linear Orderying Polytope** exactly mirrors the properties that emerge from combinations of experts.