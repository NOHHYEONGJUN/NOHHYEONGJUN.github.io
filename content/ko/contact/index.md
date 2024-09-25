---
title: Contact
date: 2024-09-24
type: landing

sections:
  - block: contact
    content:
      title: Contact
      subtitle:
      text: |-
        연락주세요!
      # Contact (edit or remove options as required)
      email: nhj7804@jbnu.ac.kr
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 백제대로
        city: 전주시
        region: 전라북도
        postcode: '94305'
        country: South Korea
        country_code: KR
      directions: 512호
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
      
      # Map
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'

      # Automatically link email and phone or display as text?
      autolink: true

      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false

    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="../../contact/" cta_text="연락하기" %}}
    design:
      columns: '1'

# Map configuration
features:
  map:
    provider: 'mapnik'
    api_key: ''
    zoom: 15
---