---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Let's talk.
    content: |
      # Ask me anything related.

      Hate Form?

      then mail me at abdullah@xyz.zyx
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
        default_value: Your name
        options: []
      - input_type: email
        name: email
        label: Email
        is_required: true
        default_value: Your email address
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select your Issue
        options:
          - Error on the site
          - Agencies
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
      - input_type: tel
        name: mobile
        label: Mobile
        default_value: Your mobile number
        options: []
        is_required: false
        type: form_field
    submit_label: Send Message
    subtitle: Fill out the form below and I will get in touch within 1 business day.
    hide_labels: false
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
