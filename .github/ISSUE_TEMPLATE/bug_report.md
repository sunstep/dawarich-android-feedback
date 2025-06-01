name: Bug Report 🐞
description: Report something that isn’t working as expected.
title: "[Bug] "
labels: ["bug"]
assignees: []

body:
  - type: textarea
    attributes:
      label: What happened?
      description: Please describe the issue in detail.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to reproduce
      description: List clear steps so we can reproduce the issue.
      placeholder: |
        1. Open the app
        2. Navigate to...
        3. Tap...
        4. See the error
    validations:
      required: true

  - type: input
    attributes:
      label: App version
      description: You can currently find the app version in the play store listing.
      placeholder: e.g. 1.0.0-beta.3
    validations:
      required: true

  - type: input
    attributes:
      label: Device & OS
      placeholder: e.g. Samsung Galaxy S23+, Android 15

  - type: textarea
    attributes:
      label: Additional context
      description: Add any screenshots, logs, or notes here.
