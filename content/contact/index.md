---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contacto
      text: |-
        Si te llama la atención los microorganismos o te interesa la fisiología o la ecología microbiana......contáctanos!
      email: roberto.orellana@upla.cl
      # phone: 888 888 88 88
      address:
        street: Fac. de Ciencias Naturales y Exactas, Universidad de Playa Ancha. Subida Leopoldo Carvallo 270, Playa Ancha 
        city: Valparaíso
        region: Valparaíso
        postcode: '2360002'
        country: Chile
        # country_code: US
      coordinates:
        latitude: '33.021135'
        longitude: '71.641563'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Lunes a Viernes 9:00 to 17:00'
       #  - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
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
