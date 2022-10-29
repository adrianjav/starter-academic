---
# An instance of the Contact widget.
widget: contact
active: false

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
      captcha: true
  
  # Contact details (edit or remove options as required)
  email: ajavaloy@cs.uni-saarland.de
  phone: ""
  address: {}
    #street: ""
    #city: Saarbücken
    #region: ""
    #postcode: ""
    #country: Germany
    #country_code: DE
  coordinates: {}
  directions: "" # Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours: []
  appointment_url: [] # 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    #- icon: skype
      #icon_pack: fab
      #name: Skype Me
      #link: 'skype:echo123?call'
    #- icon: keybase
      #icon_pack: fab
      #name: Chat on Keybase
      #link: 'https://keybase.io/'
    #- icon: comments
      #icon_pack: fas
      #name: Discuss on Forum
      #link: 'https://discourse.gohugo.io'

design:
  columns: '2'
---
