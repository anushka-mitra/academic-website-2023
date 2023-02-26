---
# Leave the homepage title empty to use the site title
title: Anushka Mitra
date: 2022-10-24
type: landing
---
sections:
  - block: hero
    content:
      title: Anushka Mitra
      image: 
        # Reference an image in your `assets/media/` folder
        filename: hero-academic.png
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Get Started
        url: https://wowchemy.com/templates/
        #icon_pack: fas
        #icon: download
      # Add your Hero text here
      text: |-
        **Welcome to my website!**
        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>        
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        gradient_end: ''
        gradient_start: ''
        text_color_light: false     
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    content:
      title: Research
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 # - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

---
