---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: 
        image:
          # Add your image background to `assets/media/`.
          filename: 'background 2.png'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'

  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2

  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: ""
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: false
  #  design:
  #    view: citation

  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    view: article-grid
  #    columns: 1

  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    page_type: post
  #    count: 5
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    offset: 0
  #    order: desc
  #  design:
  #    view: date-title-summary
  #    spacing:
  #      padding: [0, 0, 0, 0]

  - block: list
    id: Awards
    content:
      title: Awards & Fellowships
      subtitle: ''
      text: ''
      items:
        - title: "Best Paper Award"
          year: 2024
          description: "Operations Management Conference"
        - title: "Graduate Fellowship"
          year: 2023
          description: "University of X"
        - title: "Dean's Excellence Award"
          year: 2022
          description: "College of Business"
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: collection
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: ''
      items:
        - title: "Supply Chain Modeling and Optimization (OM+BAX 338)"
          date: "Fall 2024, Spring 2025, Fall 2025"
          company: "University of Texas at Austin"
          description: "Teaching Assistant"
          text: ""
    page_type: post
    count: 0
    filters:
      category: ""
      tag: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
    offset: 0
    order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
