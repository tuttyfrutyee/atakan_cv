---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-03
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Journal Publications
      filters:
        folders:
          - publication
        featured_only: true
      count: 7      
    design:
      columns: '2'
      view: card 
  - block: collection
    id: conf
    content:
      title: Conference Proceedings
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: card       
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
---
