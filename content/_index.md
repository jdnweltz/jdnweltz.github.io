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
      text: |-
        - I will be co-organizing and serving as discussant for an invited session entitled **"Study designs for social networks at different stages of the experimental process"** at JSM in August.
        - I won a **Best Student Paper Award** for the Health Policy Statistics Section for my paper, **"Reinforcement Learning for Respondent-Driven Sampling"**. I will be presenting on this work in the HPSS invited session at JSM in August.
        - I recently submitted my paper, [Reinforcement Learning for Respondent-Driven Sampling](https://arxiv.org/abs/2501.01505)
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
  - block: collection
    content:
      title: Selected Working Papers
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: true
      columns: 3
  - block: markdown
    id: teachingmark
    content:
      title: Teaching
      text: |-
        **The Complexity Global School for Emerging Political Economies:**
          - Instructor, *Statistics*, July 2025

        **Duke University:**
          - Teaching Assistant, *STA210- Regression Analysis*, Spring 2024
          - Teaching Assistant, *STA642- Time Series and Dynamic Models*, Fall 2021
          - Teaching Assistant, *STA721- Linear Models*, Fall 2020
          - Teaching Assistant,*STA102- Introduction to Biostatistics*, Spring 2020
  - block: resume-experience
    content:
      title: Industry Experience
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
  - block: collection
    id: allpapers
    content:
      title: All Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: list
      columns: 2
---
