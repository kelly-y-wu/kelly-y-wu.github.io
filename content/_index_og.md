---
date: "2022-10-24"
design:
  spacing: 6rem
sections:
- block: resume-biography-3
  content:
    button:
      text: CV
      url: https://www.dropbox.com/scl/fi/twcpj2iompgmppr05od7r/CV_Dec.pdf?rlkey=03d7nkw3rm25q2fj29nd6kwxn&st=s349esax&dl=0 #uploads/CV_Dec.pdf
    text: ""
    username: admin
  design:
    ccs_style: "color: black"
    background:
      color: system
      image:
        filename: foggy-forest-adobe-stock.svg #stacked-peaks.svg
        filters:
          brightness: 1.2
        parallax: true
        position: center 
        size: 110%
    css_class: "" #dark
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Research
  design:
    columns: 1
    view: article-grid
  id: papers
- block: markdown
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: 'Teaching'
    subtitle: ''
    text: |-
        #### Teaching Assistant, UC Davis 
        - ARE 100B Intermediate Microeconomics (2020, 2021)
        - ARE 115A Economic Development (2019, 2021, 2022)
  design:
    columns: 1
    view: article-grid
  id: teaching
- block: cta-card
  content:
    button:
      text: Get Started
      url: https://hugoblox.com/templates/
    text: |-
      This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

      <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

      Easily build anything with blocks - no-code required!

      From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
    title: "\U0001F449 Build your own academic website like this"
  demo: true
  design:
    card:
      css_class: bg-primary-700
      css_style: ""
title: ""
type: landing
---
