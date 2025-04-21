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
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'News'
      subtitle: ''
  #    text: |-
  #      Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #      I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #      Please reach out to collaborate 😃
  #  design:
  #    columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: resume-experience
    id: teaching
    content:
      title: Teaching
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Teaching Assistant
          company: Duke University
          company_url: 'duke.edu'
          #company_logo: org-x
          location: New York
          date_start: '2024-01-01'
          date_end: '2024-05-25'
          description: STA210- Regression Analysis
        - title: Teaching Assistant
          company: Duke University
          company_url: 'duke.edu'
          #company_logo: org-x
          location: New York
          date_start: '2021-09-05'
          date_end: '2021-12-05'
          description: STA642- Time Series and Dynamic Models
        - title: Teaching Assistant
          company: Duke University
          company_url: 'duke.edu'
          #company_logo: org-x
          location: New York
          date_start: '2020-09-05'
          date_end: '2020-12-05'
          description: STA721- Linear Models
        - title: Teaching Assistant
          company: Duke University
          company_url: 'duke.edu'
          #company_logo: org-x
          location: New York
          date_start: '2020-01-05'
          date_end: '2020-05-27'
          description: STA102- Introduction to Biostatistics
    design:
      columns: '2'
  #- block: collection
  #  content:
  #    title: Publications
  #    text: ""
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: false
  #  design:
  #    view: citation
---
