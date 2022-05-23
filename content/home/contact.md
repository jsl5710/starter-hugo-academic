---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: test@example.org
  phone: 954 864 4494
  address:
    street: 123 S Burrowes St
    city: State College
    region: PA
    postcode: '16801'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.792263'
    longitude: '-77.863333'
  directions: Penn State, Innovation Hub, 4th Floor.
  office_hours:
    - 'Friday 10:00 to 12:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'jsl5710@psu.edu'

design:
  columns: '2'
---
