---
name: Bug report
about: Reporta un error
title: ""
labels: "🐞 Bug"
assignees: ""

---

# Importante

- [ ] Verifiqué que este problema ya no se hubiese reportado

body:
  - type: textarea
    id: description
    attributes:
      label: "Descripción"
      placeholder: Una breve descripción del error...
    validations:
      required: true
  - type: input
    id: reprod-url
    attributes:
      label: "URL"
      placeholder: ex. https://google.com/
      description: Si es necesario dirigirse a una url en específico, ingrésela.
    validations:
      required: false
  - type: textarea
    id: reprod
    attributes:
      label: "Pasos para reproducir"
      value: |
        1. Ir a '...'
        2. Click en '....'
        3. Scroll en '....'
        4. Error
      render: bash
    validations:
      required: true
  - type: textarea
    id: screenshot
    attributes:
      label: "Screenshots"
      description: Si es necesario, adjunte capturas de pantalla del error.
      value: |
        ![DESCRIPTION](LINK.png)
      render: bash
    validations:
      required: false
  - type: textarea
    id: logs
    attributes:
      label: "Logs"
      description: Si aplica, pegue cualquier salida relevante del error. Se formateará automáticamente como código, por lo que no es necesario utilizar comillas invertidas.
      render: bash
    validations:
      required: false
  - type: dropdown
    id: browsers
    attributes:
      label: "Browsers"
      description: Si aplica, indique en que browser/(s) ocurre el error.
      multiple: true
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge
        - Opera
    validations:
      required: false
  - type: dropdown
    id: os
    attributes:
      label: "OS"
      description: Si aplica, indique en que sistema operativos/(s) ocurre el error.
      multiple: true
      options:
        - Windows
        - Linux
        - Mac
    validations:
      required: false