---
title: Contact
date: 2025-09-02
type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |- 
        This is the contact page for the Victorian GAP
      email: geometry.analysis.pde@gmail.com
      # phone: 888 888 88 88
      address:
      #  street: Locked Bagt 20000
      #  city: Geelong
      #  region: Vic
      #  postcode: '3220'
        country: Australia
        country_code: AU
      #coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
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
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
