---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 90%
      icon: chalkboard-user
      icon_pack: fas
      name: Teaching
    - description: 100%
      icon: atom
      icon_pack: fas
      name: Corrrosion
    - description: 60%
      icon: utensils
      icon_pack: fas
      name: Cooking
    title: Skills
- block: experience
  content:
    date_format: Dec 2022
    items:
    - company: UNB
      company_logo: unb
      company_url: "https://www.unb.ca/mamce/"
      date_end: ""
      date_start: "2022-11-11"
      description: |2-
          Responsibilities include:

          * Supervising Research Projects
          * In-depth study of Corrosion
          * Additive Manufacturing
      location: Canada
      title: Postdoctoral Researcher
    - company: University of Tabriz
      company_logo: tabriz
      company_url: "https://tabrizu.ac.ir/en"
      date_end: "2017-12-31"
      date_start: "2013-01-01"
      description: Worked as a researcher with extensive teaching responsibilities.
      location: Iran
      title: Research Assistant
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.nserc-crsng.gc.ca/index_eng.asp
      date_end: ""
      date_start: "2019-01-01"
      description: ""
      organization: NSERC
      organization_url: https://www.coursera.org
      title: Funding
      url: ""
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Stanford
      country: United States
      country_code: US
      postcode: "E3B 2Y1"
      region: CA
      street: 450 Serra Mall
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: test@example.org
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
    phone: 506 ??? ?? ??
    subtitle: null
    text: Please write your inquiry here.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
