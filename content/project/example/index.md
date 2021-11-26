widget: portfolio
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...

content:
  # Page type to display. E.g. project.
  page_type: project

# Uncomment to only show content with specific tags
#  filters:
#    tags:
#      - featured project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '2'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact  
  #   3 = Card
  #   5 = Showcase
  view: 3
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
draft: false
slides: example
url_pdf: ""
title: Dynamics of a rigid bouncing capsule
subtitle: Singapore Young Physicist Tournament 2021
date: 2016-04-27T00:00:00.000Z
summary: Crazy tic tac bounce ?!
url_video: ""
featured: false
external_link: Physics
url_slides: ""
tags:
  - Physics
categories:
  - Physics
links: []
image:
  caption: ""
  focal_point: Smart
  preview_only: false
url_code: ""
---
A capsule shaped object, unlike a sphere, can bounce higher than its initial height when it is imparted with an initial spin. In this project, the dynamics of a bouncing rigid capsule was investigated. A novel set-up was constructed to vary the drop height and initial angular velocity, while keeping the initial translational velocity to be 0. Video data of dropping capsule was collected using a high-speed camera with 960 fps. The translational and angular velocity of the capsule was tracked with Python OpenCV using the k-nearest algorithm. Concepts of spring-mass-damper system, and Hertzian contact were used to fully model the bouncing dynamics of the capsule, shown from the agreement between our experiments and results.
