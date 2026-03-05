---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'ACE-Health: **A**I-driven **C**limate **E**xtremes attribution, multiscale **Health** projection, and climate-health burden mitigation'
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
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - events
    design:
      view: date-title-summary
      columns: 1

  - block: collection
    id: news
    content:
      title: Recent News
      count: 5
      filters:
        folders:
          - blog
      order: desc
    design:
      view: date-title-summary

  - block: contact-info
    id: contact
    content:
      title: Contact
      email: tao.huang@ntu.edu.sg
      address: 'Nanyang Technological University, Singapore'
---
