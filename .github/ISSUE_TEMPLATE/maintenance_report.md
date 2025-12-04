---
name: Maintenance Report
description: Report maintenance tasks, refactoring, or housekeeping needs
title: "Maintenance: "
labels: [maintenance]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting a maintenance task!

  - type: textarea
    id: description
    attributes:
      label: Description
      description: A clear and concise description of the maintenance task
      placeholder: Describe the maintenance task here...
    validations:
      required: true

  - type: textarea
    id: reason
    attributes:
      label: Reason for Maintenance
      description: Why is this maintenance task necessary?
      placeholder: This task is needed because...
    validations:
      required: true

  - type: textarea
    id: scope
    attributes:
      label: Scope of Work
      description: What specific areas or components are affected?
      placeholder: The work will involve...
    validations:
      required: true

  - type: textarea
    id: impact
    attributes:
      label: Impact
      description: What is the expected impact of this maintenance?
      placeholder: This will improve...
    validations:
      required: true

  - type: textarea
    id: dependencies
    attributes:
      label: Dependencies
      description: Are there any dependencies or prerequisites?
      placeholder: This task depends on...

  - type: textarea
    id: timeline
    attributes:
      label: Estimated Timeline
      description: How long do you expect this maintenance to take?
      placeholder: This should take approximately...

  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our Code of Conduct
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
