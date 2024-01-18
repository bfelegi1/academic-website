---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
         Feel free to contact me with any questions!
      # Contact (add or remove contact options as necessary)
      email: bfelegi@vt.edu
      phone: +1 (540) 231-4431
      appointment_url:
      address:
        street: 3122 Pamplin Hall, 880 West Campus Drive
        city: Blacksburg
        region: VA
        postcode: '24060'
        country: United States
        country_code: US
      directions:
      office_hours:
        - 'By Appointment Only'
    
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '37.2286'
        longitude: '-80.4248'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Follow Me on Twitter
          link: 'https://twitter.com/BFelegi'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
