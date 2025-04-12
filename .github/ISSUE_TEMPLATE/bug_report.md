---
name: 🐛 Bug Report
description: Report a reproducible software bug.
labels: bug
body:
  - type: input
    id: title
    attributes:
      label: Bug Summary
      description: Clear and concise summary of the problem
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Describe the bug in detail. Include what you expected vs. what happened.
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: How can we reproduce the issue? Be as detailed as possible.
    validations:
      required: true

  - type: input
    id: environment
    attributes:
      label: Environment
      description: Firmware/app version, hardware model, browser (if applicable)

  - type: textarea
    id: additional
    attributes:
      label: Additional Information
      description: Screenshots, logs, related issues, etc.
---