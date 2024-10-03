---
widget: portfolio
headless: true

title: "Learning Hub"
subtitle: "나의 학습 프로젝트"

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
  columns: '2'
  view: custom
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, "120px", 0]}
  custom_view: 'card_partial'
---