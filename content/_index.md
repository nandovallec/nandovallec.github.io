---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I’m a Ph.D. candidate at Simula Research Laboratory working on LLM-Based Automatic Software Improvement—teaching large language models to detect bugs, refactor code, and optimize performance with minimal human guidance. My goal is to make software engineering faster, safer, and more sustainable.

        I build practical ML systems informed by a global journey through Spain, the U.S., Germany, Sweden, and Japan, and I’m especially curious about the intersection of AI and cybersecurity: secure-by-default code generation, anomaly detection in CI/CD, and trustworthy tooling for developers.

        What I’m exploring now:

        - Self-refining agents for code repair and performance tuning
        - Robust evaluation of AI-generated patches (correctness, security, maintainability)
        - Data pipelines for code intelligence (mining repos, tracing, and feedback loops)
        - Privacy-preserving and safety-first practices for AI in software development

        If you’re working on developer tools, secure AI, or code intelligence, let’s talk and collaborate 😃
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: resume-languages
    content:
      title: Languages
      username: admin
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
---
