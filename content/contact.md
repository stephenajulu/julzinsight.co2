---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      At Julz Insight, we are dedicated to delivering scalable, enterprise-grade digital foundations to forward-thinking organizations, businesses, and enterprises interested in keeping their data and systems within their control. Whether you have a question, need support, or want to discuss a potential infrastructure audit, we are here to help. Get in touch with us through any of the following methods:


      ***


      General Inquiries: info@julzinsight.co
      Secondary Email (CC): julzinsight@gmail.com
      For Support: support@julzinsight.co
      Phone: +254 (0) 740 128 010
      Address: Syokimau, Nairobi, Kenya


      Social Media: Follow us on:
      - Twitter: @julzinsight
      - LinkedIn: Julz Insight
      - Instagram: @julzinsight
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
          - Managed Open Source Business Infrastructure
          - Strategic IT Advisory
          - Schedule an Infrastructure Audit
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that Julz Insight is storing my submitted information, so I
          can be contacted.
    submit_label: Send Message
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
