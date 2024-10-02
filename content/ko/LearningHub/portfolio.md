---
widget: portfolio
headless: true
weight: 30
title: 프로젝트
subtitle: ''

content:
  page_type: project
  filter_default: 0
  filter_button:
    - name: 전체
      tag: '*'
    - name: 클라우드
      tag: Cloud
    - name: 컨테이너 오케스트레이션
      tag: CO
    - name: 네트워크 가상화
      tag: NV
    - name: DevOps & 자동화
      tag: CICD

design:
  columns: '1'
  view: custom
  flip_alt_rows: false

advanced:
  css_style: ""
  css_class: ""
---

{{< portfolio_card >}}

<h2 style="margin-top: 40px;">프로젝트 목록</h2>

{{< portfolio_list >}}