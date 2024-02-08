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
            brightness: 1
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome to "Microrobotic Biomedical Systems" group 👋'
      subtitle: ""
      text: |-
        We engineer intelligent microrobots for biomedical applications in targeted drug delivery, microsurgery, detoxification, and diagnostics by advancing micro- and nanofabrication as well as ultrasound technologies. To realize their full potential, medical microrobots have to master locomotion in complex biofluidic environments, wireless actuation and control, precise imaging and localization, or effective drug/cargo delivery. We overcome these challenges by incorporating biologically-inspired adaptive capabilities into microrobotic agents and utilize lab-on-a-chip and microfluidic systems to validate biological and therapeutic functions. We thus bridge the gap between biomedical research and clinical applications to propel medical microrobots to the forefront of modern healthcare.

        ![](MBS_Words.png)

        ## Open Positions
        - I have multiple **PhD positions** in my group, click [here](/team) for more information!
        - We are also hiring PhD students through IMPRS-IS program, apply [here](https://imprs.is.mpg.de/application)! -- **The position is closed now!**

        ## About Me:
        I am a tenure-track Professor in Biomedical Systems at the University of Stuttgart, where I lead the [Microrobotic Biomedical Systems](https://www.bio.uni-stuttgart.de/MicBioSys/) group in Faculty 04, [IBBS](https://www.bio.uni-stuttgart.de/en/). Previously, I was a Lecturer (Assistant Professor) in Mechanical Engineering at [Newcastle University](https://www.ncl.ac.uk). Prior to that, I was a postdoctoral fellow at [Max Planck Institute for Intelligent Systems](https://pi.is.mpg.de/), Department of Physical Intelligence in Stuttgart, Germany. I obtained my Ph.D. in Mechanical Engineering from [Koc University](https://www.ku.edu.tr/en), Turkey, in 2018. I got my B.Sc. in Mechanical Engineering from [Sharif University of Technology](https://en.sharif.edu/) in 2012.

        ---
    design:
      columns: "1"

  - block: collection
    content:
      title: News
      subtitle: ""
      text:
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

  - block: collection
    content:
      title: Featured Articles
      subtitle: ""
      text:
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: "Aghakhani, Amirreza"
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
      columns: "2"
---
