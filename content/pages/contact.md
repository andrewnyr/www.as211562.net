---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Contact
sections:
  - type: CtaSection
    elementId: ''
    colors: colors-f
    backgroundSize: full
    title: contact us
    text: null
    actions: []
    backgroundImage:
      url: /images/grad.svg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    elementId: ''
    colors: colors-h
    backgroundSize: full
    form:
      type: FormBlock
      elementId: contact-form
      action: 'https://usebasin.com/f/0a8a47673728'
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
          hideLabel: true
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
          hideLabel: true
        - type: SelectFormControl
          name: subject
          label: Subject
          hideLabel: true
          defaultValue: Please choose...
          options:
            - New York
            - San Francisco
          isRequired: false
          width: full
        - type: TextareaFormControl
          name: message
          label: message
          hideLabel: true
          placeholder: Message
          isRequired: false
          width: full
      submitLabel: Send Message
    media: null
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
