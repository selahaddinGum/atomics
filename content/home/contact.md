---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  #email: test@example.org
  #phone: 888 888 88 88
  address:
    street: 1 Prospect St
    city: Providence 
    region: RI
    postcode: '02912'
    country: United States
    country_code: US
  coordinates:
    latitude: '41.826820'
    longitude: '-71.402931'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday-Friday during business hours'  
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: '1'
---

If you are interested in what we're doing or have any questions, we would love to hear from you.

