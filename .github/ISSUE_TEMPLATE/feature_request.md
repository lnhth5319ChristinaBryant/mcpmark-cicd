---
name: Feature Request
description: Suggest an idea or enhancement for this project
title: "Feature: "
labels: [enhancement]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for suggesting a new feature!

  - type: textarea
    id: description
    attributes:
      label: Description
      description: A clear and concise description of the feature request
      placeholder: Describe the feature you'd like to see...
    validations:
      required: true

  - type: textarea
    id: problem
    attributes:
      label: Problem Statement
      description: What problem does this feature solve?
      placeholder: I'm trying to...
    validations:
      required: true

  - type: textarea
    id: solution
    attributes:
      label: Proposed Solution
      description: How should this feature work?
      placeholder: The feature should...
    validations:
      required: true

  - type: textarea
    id: alternatives
    attributes:
      label: Alternative Solutions
      description: What alternative solutions have you considered?
      placeholder: I've considered...

  - type: textarea
    id: benefits
    attributes:
      label: Benefits
      description: What benefits would this feature provide?
      placeholder: This would help by...

  - type: textarea
    id: examples
    attributes:
      label: Examples
      description: Provide examples of how this feature would be used
      placeholder: For example...

  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our Code of Conduct
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
