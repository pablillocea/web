---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-05-22
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🔍 My Research Focus'
      subtitle: ''
      text: |-
        The sociology of education is a significant chapter in the sociology of knowledge and power, as well as the philosophies of power. Often misjudged as merely an applied science fit only for educators, it actually forms the foundation of a broader anthropology of power and legitimacy. This discipline helps us understand the mechanisms behind the reproduction of social structures and the mental frameworks that, being linked to these structures, obscure their true nature and reinforce their legitimacy. In advanced societies, social differentiation is driven by economic and cultural capital. The educational system, crucial in distributing cultural capital, thus plays a key role in maintaining social hierarchies and becomes a central battleground for controlling dominant positions.

        (Adapted from the prologue of *The State Nobility* by P. Bourdieu)
    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#     text: ''
#     # Page type to display. E.g. post, talk, publication...
#     page_type: post
#     # Choose how many pages you would like to display (0 = all pages)
#     count: 5
#     # Filter on criteria
#     filters:
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
#     view: date-title-summary
#     # Reduce spacing
#     spacing:
#       padding: [0, 0, 0, 0]

---
