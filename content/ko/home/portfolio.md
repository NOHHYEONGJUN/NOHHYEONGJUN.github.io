---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
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

  # Card design settings
  card:
    # Set a fixed height for all cards
    height: '400px'  # Adjust this value as needed
    text_color: 'black'
    background: 'white'

  # Grid settings
  view_options:
    # Set to display 3 columns on desktop
    columns_desktop: 3
    # Set to display 2 columns on tablet
    columns_tablet: 2
    # Set to display 1 column on mobile
    columns_mobile: 1

---
