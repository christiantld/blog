---
title: Contato 📬
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Preencha os campos abaixo para entrar em contato .
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - type: text
        name: name
        label: Nome
        default_value: Seu Nome
        is_required: true
      - type: email
        name: email
        label: Email
        default_value: Seu Email
        is_required: true
      - type: select
        name: subject
        label: Assunto
        default_value: Selecione uma opção
        options:
          - Contato
          - Dúvidas
          - Erro no site
          - Outro
      - type: textarea
        name: message
        label: Mensagem
        default_value: Sua Mensagem
    submit_label: Enviar Mensagem
template: advanced
---
