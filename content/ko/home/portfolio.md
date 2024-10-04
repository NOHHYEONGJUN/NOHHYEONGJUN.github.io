---
widget: portfolio
headless: true
weight: 20
title: 'Portfolio'
subtitle: ''

content:
  page_type: project
  filter_default: 0
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
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, 0, 0]}

  view_options:
    theme: custom
    columns: 3
    rows: 3
    show_more: true
    show_more_text: 'Load More'
    show_more_type: js
---