---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.9
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: "Welcome 👋"
      subtitle: ""
      text: |-
        I am a tenure-track Professor in Biomedical Systems at the University of Stuttgart, where I lead the **Microrobotic Biomedical Systems** group. Previously, I was a Lecturer (Assistant Professor) in Mechanical Engineering at [Newcastle University](https://www.ncl.ac.uk). Prior to that, I was a postdoctoral fellow at [Max Planck Institute for Intelligent Systems](https://pi.is.mpg.de/), Department of Physical Intelligence in Stuttgart, Germany. I obtained my Ph.D. in Mechanical Engineering from [Koc University](https://www.ku.edu.tr/en), Turkey, in 2018. I got my B.Sc. in Mechanical Engineering from [Sharif University of Technology](https://en.sharif.edu/) in 2012.

        ---
    design:
      columns: "1"

  - block: collection
    content:
      title: Recent News
      subtitle: ""
      text: |-
        Please visit our #opportunites page

      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: "1"
---
