---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation 
  - block: contact
    id: contact
    content:
      title: Contact
      email: lixiang.chen@fu-berlin.de
      address:
        street: Habelschwerdter Allee 45
        region: Berlin
        postcode: '14195'
        country: Germany
        country_code: DE
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
