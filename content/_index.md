---
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography
    content:
      username: admin
      title: ""
      subtitle: ""
      text: |
        Carrie Giunta is an associate lecturer at the University of the Arts London (UAL). She teaches Philosophy at Central Saint Martins, UAL on the MRes Art: Theory and Philosophy course, and on the BA Sound Arts course at London College of Communications,UAL. She holds a doctorate in Philosophy from the University of Dundee. In 2016, Carrie co-edited the book Nancy and Visual Culture (Edinburgh University Press). She is a member of the Society for Women in Philosophy UK, the Society for Women in Philosophy Italia and the Society for French Studies. Her forthcoming publications include an essay in the edited volume Nancynéma, published by UGA Éditions. Between 1995 and 2009 Carrie worked in cinema as a sound editor and was part of the BAFTA-winning sound team on Casino Royale.
      
    design:
      # Apply a gradient background
      css_class:
      background:
        color: #ffffff
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
        [Learn more]()
        subtitle: "Visiting Researcher"
        - University of Palermo Humanities Department, Italy
        - University of Urbino Humanities Department, Italy
        subtitle: "Book"
        subtitle: "Doctorate"
        subtitle: "Casino Royale"
        subtitle: "Berlinale Talent Campus"   

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
