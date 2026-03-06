---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: circle

  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      columns: 1

  - block: collection
    id: news
    content:
      title: News
      count: 10
      filters:
        folders:
          - blog
      order: desc
    design:
      view: date-title-summary
---
