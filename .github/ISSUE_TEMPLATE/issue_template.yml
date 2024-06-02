---
name: Issue report
description: Create a report to help us improve
title: '[ISSUE]: '
labels: ''
assignees: ['@jared-bloomer']
body:
  - type: dropdown
    id: os
    attributes:
      label: Which Operating system are you using?
      description: Which Operating system are you using? Windows? Linux? OS X?
      multiple: true
      options:
       - Windows 10
       - Windows 11
       - Linux (Debian Based)
       - Linux (Redhat Based)
       - OS X (Please include version in description)
  - type: dropdown
    id: version
    attributes:
      label: Which Version of this application are you using?
      description: Which Version (Github Release) of this application are you using?
      multiple: false
      options:
        - 1.0.x
  - type: textarea
    id: issue-description
    attributes:
      label: What is the issue?
      description: Tell us what this issue is about
    validations:
      required: true
  - type: textarea
    id: reproduction-steps
    attributes:
      label: How do we reproduce the Bug
      description: How can we replicate and confirm this issue?
    validations:
      required: true
