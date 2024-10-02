---
# Portfolio widget
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Learning Hub
subtitle: '나의 학습 프로젝트'

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
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false

  # Apply a background color, gradient, or image.
  background:
    # Apply a background color.
    color: "white"
    # Add a gradient
    gradient_start: "#4bb4e3"
    gradient_end: "#2b94c3"
    # Add an image
    # image: "background.jpg"  # Name of image in `static/media/`.
    # image_darken: 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    # image_size: "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
    # image_position: "center"  # Options include `left`, `center` (default), or `right`.
    # image_parallax: true  # Use a fun parallax-like fixed background effect? true/false

  # Customize the section spacing. Order is top, right, bottom, left.
  spacing:
    padding: ["20px", "0", "20px", "0"]
---