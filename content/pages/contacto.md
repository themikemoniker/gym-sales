---
type: PageLayout
title: Contacto
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
    subtitle: ''
    text: >
      Feel free to contact us with any inquiries. This form will alert us via
      email and you can also reach out over whatsapp




      Whatsapp: +52 555-5555
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Tu nombre
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submito
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /contacto
seo:
  type: Seo
  metaTitle: Contact page
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
