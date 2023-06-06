---
# Leave the homepage title empty to use the site title
title: Isabel Hovdahl
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 # - block: collection
 #   id: posts
 #   content:
 #     title: Recent Posts
 #     subtitle: ''
 #     text: ''
 #     # Choose how many pages you would like to display (0 = all pages)
 #     count: 5
 #     # Filter on criteria
 #     filters:
 #       folders:
 #         - post
 #       author: ""
 #       category: ""
 #       tag: ""
 #       exclude_featured: false
 #       exclude_future: false
 #       exclude_past: false
 #       publication_type: ""
 #     # Choose how many pages you would like to offset by
 #     offset: 0
 #     # Page order: descending (desc) or ascending (asc) date.
 #     order: desc
 #   design:
 #     # Choose a layout view
 #     view: compact
 #     columns: '2'
 # - block: markdown
 #   id: current
 #   content:
 #     title: Work in progress
 #     text: Add text here
 #   design:
 #     columns: '2'
  - block: collection
    id: working
    content:
      title: Working papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: list
  - block: collection
    id: published
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: 
        At NHH, I teach the following courses\:
        
        * item1
        
        * item2
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      email: isabel.hovdahl@nhh.no
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
