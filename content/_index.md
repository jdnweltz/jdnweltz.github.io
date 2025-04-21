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
  - block: markdown
    id: teachingmark
    title: Teaching
    text: |-
      The Complexity Global School for Emerging Political Economies:
        - Instructor, July 2025
      Duke Univerity:
        - Teaching Assistant, STA210- Regression Analysis, Spring 2024
        - Teaching Assistant, STA642- Time Series and Dynamic Models, Fall 2021
        - Teaching Assistant, STA721- Linear Models, Fall 2020
        - Teaching Assistant,STA102- Introduction to Biostatistics, Spring 2020
  - block: resume-experience
    title: Professional Experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
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
