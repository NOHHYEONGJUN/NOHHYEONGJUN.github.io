---
# Slider section
widget: slider
weight: 30  # portfolio의 weight가 20이므로, 30으로 설정하여 그 아래에 위치하도록 합니다.
active: true
headless: true  # This file represents a page section.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 3000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: '350px'

content:
  slides:
    - title: <span style="font-size:70%">Container Orchestration</span>
      content: <span style="font-size:70%">Kubernetes / Docker</span>
      align: center
      background:
        image:
          filename: container-orchestration.png
          filters:
            brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Cloud</span>
      content: <span style="font-size:70%">AWS / OpenStack</span>
      align: center
      background:
        image:
          filename: Cloud.png
          filters:
            brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Network Virtualization</span>
      content: <span style="font-size:70%">Network / ONOS / OpenAirInterface</span>
      align: center
      background:
        image:
          filename: network-virtualization.png
          filters:
            brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">DevOps & Automation</span>
      content: <span style="font-size:70%">GitLab / Jenkins / Harbor / ArgoCD / SonarQube</span>
      align: center
      background:
        image:
          filename: DevOps.jpeg
          filters:
            brightness: 0.4
        position: center
        color: '#000'

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
---