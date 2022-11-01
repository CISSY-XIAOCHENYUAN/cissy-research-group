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
  email: xcyuan@mpu.edu.mo
  phone: +853-85996434
  address:
    street: R. de Luís Gonzaga Gomes
    city: Macau 


  coordinates:
    latitude: '22.1936'
    longitude: '113.5518'
  directions: Office A313, Chi Un Building
  office_hours:
    - 'Monday to Friday 10:00 to 18:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
