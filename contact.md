---
title: Contato
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Para entrar em contato preencha os dados abaixo
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Seu nome
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Seu melhor endereço de email
        is_required: true
      - input_type: select
        name: subject
        label: Assunto
        default_value: Por favor, selecione
        options:
          - Quer me contratar?
          - Gostaria de oferecer comentários a respeito dos posts do blog.
          - Outros
      - input_type: textarea
        name: message
        label: Mensagem
        default_value: Sua mensagem
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que as informações contidas nesse formulário serão visíveis e gostaria de ser contatado através delas.
    submit_label: Enviar mensagem
seo:
  title: Contact
  description: Essa é uma página de contato
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: Essa é uma página de contato
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contato
    - name: 'twitter:description'
      value: Essa é uma página de contato
layout: advanced
---
