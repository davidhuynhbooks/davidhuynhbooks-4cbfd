---
title: Shop Books
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |+
      All my books are available for purchase from Amazon around the world.

      ***

      ## If you are in the Dallas, TX area you can also find the books at:

      ### MeLisa the Pie Lady

      3805 Main St.
      The Colony, Texas 75056
      [melisathepielady.com](https://melisathepielady.com)
      (Eat some delicious pies while you read my books.)

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Branding
          - Design
          - Digital
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
    hide_labels: true
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
