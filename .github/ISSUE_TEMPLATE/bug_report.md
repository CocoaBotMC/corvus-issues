name: Bug Report
description: Corvus does not work as described.
labels: ["Type: Bug"]
body:
  - type: input
    attributes:
      label: Your Discord tag line
      description: Discord username.
      placeholder: '@addman'
    validations:
      required: true

  - type: input
    attributes:
      label: Discord Client ID
      description: You can get this by following this -> https://cdn.ooaddman.com/MxdapV
      placeholder: 351132215700357131
    validations:
      required: true

  - type: textarea
    attributes:
      label: Describe the bug
      description: How the bot behaves when the bug happens. Detail is KEY here!
    validations:
      required: true

  - type: textarea
    attributes:
      label: Expected behavior
      description: How the bot is supposed to behave.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to reproduce
      description: What to do in order to reproduce this issue
      placeholder: |
        Step 1: ..
        Step 2: ..
    validations:
      required: true

  - type: textarea
    attributes:
      label: Additional info
      description: Anything else you want to provide that will help in resolving the issue faster, such as screenshots or videos.
    validations:
      required: false
  - type: checkboxes
    attributes:
      label: Checklist
      description: Let's make sure this report is valid
      options:
        - label: The bot has all the correct permissions
          required: true
        - label: I have made sure the player/players usernames are valid
          required: true
        - label: I ticked all of the boxes without actually reading them
          required: false
        - label: I have made this report without giving the bot time to work out the issue on it own
          required: true
