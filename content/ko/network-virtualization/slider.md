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
    - title: <span style="font-size:70%">Network Function Virtualization</span>
      content: <span style="font-size:70%">NFV</span>
      align: center
      background:
        media: NFV(unsplash).jpg
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Software-Defined Networking</span>
      content: <span style="font-size:70%">SDNspan>
      align: center
      background:
        media: SDN(unsplash).jpg
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Virtual Network Functions</span>
      content: <span style="font-size:70%">VNF</span>
      align: center
      background:
        media: VNF(unspalsh).jpg
        brightness: 0.4
        position: center
        color: '#000'

    - title: <span style="font-size:70%">Multi-access Edge Computing</span>
      content: <span style="font-size:70%">MEC / Cloud</span>
      align: center
      background:
        media: cloud(unsplash).jpg
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