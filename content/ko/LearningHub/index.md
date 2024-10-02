---
title: Learning Hub
type: landing

sections:
  - block: portfolio
    content:
      title: Learning Hub
      subtitle: 'Explore my learning journey and projects'
      text: ''
      # Page type to display. E.g. project.
      page_type: project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      filter_default: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      filter_button:
        - name: All
          tag: '*'
        - name: Cloud
          tag: Cloud
        - name: Container Orchestration 
          tag: CO
        - name: Network Virtualization
          tag: NV
        - name: DevOps & Automation
          tag: CICD
          
  design:
    columns: '1'
    view: card
    card_view_layout: small_image
    flip_alt_rows: true
    background: {}
    spacing: {padding: [0, 0, "120px", 0]}
---