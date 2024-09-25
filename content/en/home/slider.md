---
# Slider section
widget: slider
weight: 30
active: true
headless: true

interval: 3000
height: '350px'

content:
  slides:
    - title: <span style="font-size:70%">Container Orchestration</span>
      content: <span style="font-size:70%">Kubernetes / Docker</span>
      align: center
      background:
        media: container-orchestration.png
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Cloud</span>
      content: <span style="font-size:70%">AWS / OpenStack</span>
      align: center
      background:
        media: Cloud.jpg
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Network Virtualization</span>
      content: <span style="font-size:70%">Network / ONOS / OpenAirInterface</span>
      align: center
      background:
        media: network-virtualization.png
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">DevOps & Automation</span>
      content: <span style="font-size:70%">GitLab / Jenkins / Harbor / ArgoCD / SonarQube</span>
      align: center
      background:
        media: DevOps.jpeg
        brightness: 0.4
        position: center
        color: '#000'

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '500px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3000
---