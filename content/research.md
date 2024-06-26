---
# Leave the homepage title empty to use the site title
title: Research
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Research
      text: The age of big data promises to revolutionize science and engineering, but it suffers from two critical complications. First, big data introduces heterogeneity from diverse populations that can obscure causality within spurious correlations. Second, rich data gives only a fine-grained picture of the latent abstractions we use to understand the world. I study these issues through the framework of causal inference, which seeks to replace controlled experiments with mathematics on observational data. I'm especially interested in using causal mathematics to answer questions that cannot be addressed by experimentation alone.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: collection
    id: research
    content:
      title: Topics
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      sort_by: 'Weight'
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Recent Publications
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'
      view: citation

---