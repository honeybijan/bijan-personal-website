---
# Leave the homepage title empty to use the site title
title: Research
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Research
      text: Confounding emerges whenever data spans multiple populations, environments, or laboratories -- an unavoidable setting in large-scale datasets. The search for new signals in this data can awaken previously innocuous confounding effects, even further exacerbated by the unprecedented power of ML. The novelty of these phenomena conceal them from the intuitions of domain knowledge, making them silent killers of scientific rigor. My work centers around evaluating when data fusion is safe, deconfounding results when it is not safe, and the paradoxes that arise when aggregating conclusions from non-fused data sources.
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