---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-03-09
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "Habeeb A. Babatunde — Postdoctoral Researcher, Food & Dairy Innovation Center. I develop chemometric and machine-learning methods to quantify milk proteins and build reproducible open-source tools for dairy data science."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 'Download CV'
        url: 'uploads/resume.pdf' 
    design:
      css_class: dark
      background:
        color: black
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a Postdoctoral Researcher at the Food and Dairy Innovation Center, Boise State University. My work focuses on developing chemometric and machine-learning methods for quantifying milk proteins using spectroscopy, and building reproducible open-source tools for dairy data science. 

        Interested in collaboration or have a project idea? [Contact me](mailto:babatundehabeeb2@gmail.com) or [download my CV](/uploads/resume.pdf).
    design:
      css_class: dark
      background:
        color: black
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
      text: "Key peer-reviewed papers and impactful research."
    design:
      view: citation
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      text: "Invited talks and presentations will appear here."
      filters:
        folders:
          - event
    design:
      view: date-title-summary
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: 'News and updates will be posted here as they become available.'
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
