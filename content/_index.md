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
        text: Request a CV
        url: mailto:carrie.giunta@protonmail.com
      headings:
        about: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class:
      background:
        color: white
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
    
  - block: markdown
    content: ""
    title: "About This Section"
    subtitle: "Current role"
    text: |
        Associate Lecturer      
        - [MRes Art: Theory and Philosophy] (https://www.arts.ac.uk/subjects/curation-and-culture/postgraduate/mres-art-theory-and-philosophy-csm)
        External Lecturer      
        - [South, West and Wales Doctoral Training Partnership] (https://www.sww-ahdtp.ac.uk/about/about-swwdtp/)
        [Learn more](https://www.arts.ac.uk/colleges/central-saint-martins/people/carrie-giunta)
        subtitle: "Visiting Researcher"
        - University of Palermo Humanities Department, Italy
        - University of Urbino Humanities Department, Italy
        subtitle: "Book"
        subtitle: "Doctorate"
        subtitle: "Casino Royale"
        subtitle: "Berlinale Talent Campus"
    design:
      columns: "1"
      background:
        color: "white"

  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
