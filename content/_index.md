---
# Leave the homepage title empty to use the site title
title: Anushka Mitra
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      design:
      columns: '2'
  - block: collection
    content:
      title: Research
      text: 
      filters:
        folders:
          - project  
    design:
      columns: '2'
      view: compact
      
  - block: collection
    content:
      title: Teaching
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: compact
      

---
