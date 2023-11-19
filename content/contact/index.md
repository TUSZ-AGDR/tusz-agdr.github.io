---
title: Contact
date: 2023-11-17

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Please leave your message, we will back to you as early as possible.
      email: liqiang1@sztu.edu.cn
      phone: +86-0755-23256601
      address:
        street: 3002 Lantian Road, Pingshan District
        city: Shenzhen
        region: Guangdong Province
        postcode: '518118'
        country: China
        country_code: CN
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Lab--C1-905
      office_hours:
        - 'Monday-Friday 9:00 to 17:00'
      appointment_url: 'https://calendly.com'
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
