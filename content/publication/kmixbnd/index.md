---
title: 'Causal Inference Despite Limited Global Confounding via Mixture Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Spencer Gordon
  - admin
  - Yuval Rabani
  - Leonard Schulman

# Author notes (optional)
author_notes:
  - 
  - 'Author order is alphabetical'

date: '2023-04-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2nd Conference on Causal Learning and Reasoning*
publication_short: In *CLEAR 2023*

abstract: A Bayesian Network is a directed acyclic graph (DAG) on a set of $n$ random variables (the vertices); a Bayesian Network Distribution (BND) is a probability distribution on the random variables that is Markovian on the graph. A finite $k$-mixture of such models is graphically represented by a larger graph which has an additional "hidden" (or "latent") random variable $U$, ranging in $\{1,\ldots,k\}$, and a directed edge from $U$ to every other vertex. Models of this type are fundamental to causal inference, where $U$ models an unobserved confounding effect of multiple populations, obscuring the causal relationships in the observable DAG. By solving the mixture problem and recovering the joint probability distribution on $U$, traditionally unidentifiable causal relationships become identifiable. Using a reduction to the more well-studied "product" case on empty graphs, we give the first algorithm to learn mixtures of non-empty DAGs. 

# Summary. An optional shortened abstract.
summary: The first known algorithm for $k$-MixBND.

tags: ['mixtures']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2112.11602v2.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: #'https://arxiv.org/abs/2112.11602v2'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [mixtures]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---