---
date: "2023-06-05"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: Programming Language
      icon: r-project
      icon_pack: fab
      name: R
    - description: Classical and Bayesian
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: Predictive Analytics
      icon: brain
      icon_pack: fas
      name: Artificial Intelligence
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: NFU Mutual
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2022-10-26"
      description: |2-
          Responsibilities include:

          * Leading Automation & Innovation Efforts across UW&P
          * Managing Consumer Demand Models - Utilising GBMs
          * Technical and Statistical Training Co-ordinator
      location: Stratford-upon-Avon
      title: Pricing Innovation Consultant
    - company: NFU Mutual
      company_logo: org-gc
      company_url: ""
      date_end: "2022-10-26"
      date_start: "2021-07-26"
      description: |2-
          Responsibilities included:

          * Maintaining Growth & Peristancy of £160M LCI Portfolio
          * Creating Experience Rating Tools for Individual Accounts
          * Stakeholder Management with Brokers, Agents and UW
      location: Stratford-upon-Avon
      title: Large Corporate Insurance Consultant
    - company: BUPA
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Actuarial Pricing Consultant
    - company: AON
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: Manchester
      title: Actuarial Retirement Consultant
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
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
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Stratford-upon-Avon
      country: United Kingdom
      country_code: UK
      postcode: "CV37 7LW"
      street: 5 Montague Court
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: DM Me
    - icon: skype
      icon_pack: fab
      link: skype:echo123?call
      name: Skype Me
    directions: Originally from Wigan, Greater Manchester
    email: sam_parry93@hotmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday-Friday 09:00 to 18:00
    - Saturday-Sunday 10:00 to 14:00
    phone: 07949 510 894
    subtitle: null
    text: If you'd like to get in touch with me to discuss this website or to extend your network. Please use the facilities below to contact me.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
