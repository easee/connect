---
name: 💬 General Feedback
description: Share ideas, thoughts, or feedback that doesn’t fit a bug or feature request.
labels: feedback
body:
  - type: textarea
    id: summary
    attributes:
      label: What’s on your mind?
      description: Give us the gist – what are you thinking?
      placeholder: I was just gonna say...
    validations:
      required: true

  - type: textarea
    id: details
    attributes:
      label: Can you tell us a bit more?
      description: Feel free to share examples, context, or where you noticed this.
      placeholder: So here’s the thing...
    validations:
      required: true

  - type: dropdown
    id: category
    attributes:
      label: What does this relate to?
      description: Helps us send it to the right team.
      options:
        - Easee App
        - Installer App
        - Easee Fix (Web)
        - Easee Control (Web)
        - Easee Portal (Web)
        - Easee ST Portal (Legacy)
        - Hardware
        - APIs & Integrations
        - Other
    validations:
      required: true

  - type: textarea
    id: suggestions
    attributes:
      label: Got an idea?
      description: Totally optional – if you’ve got a take on how to make it better, drop it here.
      placeholder: What if it worked like this...?
---