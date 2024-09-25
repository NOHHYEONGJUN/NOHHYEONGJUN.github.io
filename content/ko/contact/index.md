---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)
  email: nhj7804@jbnu.ac.kr
  address:
    street: 백제대로
    city: 전주시
    postcode: '94305'
  coordinates:
    latitude: '35.84601324617979'  
    longitude: '127.13444961966684' 
  directions: 512호
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'

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
  columns: '2'

# Map section
map:
  provider: 'mapnik'
  zoom: 15
---

# Page type
type: landing

# Page sections
sections:
  - block: contact
    content:
      title: Contact
      subtitle:
      text: ''
      # Contact details (edit or remove options as required)
      email: nhj7804@jbnu.ac.kr
      address:
        street: 백제대로
        city: 전주시
        postcode: '94305'
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions: 512호
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
    design:
      columns: '2'