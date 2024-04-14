---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Latest Publication
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Publications
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Engineer
          company: Inria
          company_url: 'https://www.inria.fr/en'
          company_logo: inria
          location: Rennes, France
          date_start: '2021-09-01'
          date_end: '2023-10-31'
          description: |2-
            * Empirical Research Experimentation
            * [Evaluation of Micro/Learning, Compositional Prediction]({{< ref "/publication/datatime" >}}). 
            * Engineer working on the Eclipse [GEMOC Studio](https://gemoc.org/studio.html) project. 
            * Involved in the study of the migration of the GEMOC Studio to a microservices architecture, development of WEB IDE prototypes
        - title: Software Engineer - Apprenticeship
          company: Atos
          company_url: 'https://atos.net/en/'
          company_logo: atos
          location: Rennes
          date_start: '2020-09-01'
          date_end: '2021-09-01'
          description: |2-
            * Responsible for the development and validation of new feature within a J2EE SOA
              application suite focuses on telecom and big data for Orange
            * Responsible for the maintenance and evolution of an internal tool Java/Angular
        - title: Software Engineer - Trainee
          company: Atos
          company_url: 'https://atos.net/en/'
          company_logo: atos
          location: Rennes
          date_start: '2020-09-01'
          date_end: '2021-09-01'
          description: |2-
            * Led the specification, development and test of an internal application J2EE/Angular
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: romain.lefeuvre@inria.fr
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: 263 Av. Général Leclerc
        city: Rennes
        postcode: '35000'
        country: France
        country_code: FR
      directions: Building 12F, Room F325
      #office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
       # provider: netlify
       # formspree:
       #id:
       # netlify:
          # Enable CAPTCHA challenge to reduce spam?
        #  captcha: false
    design:
      columns: '2'
---
