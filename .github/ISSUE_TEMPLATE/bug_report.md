name: Bug Report
description: Report a bug to help us improve
title: "[Bug] "
labels: ["bug"]

body:

- type: markdown
  attributes:
  value: Thank you for reporting a bug! Please fill out the form below.

- type: textarea
  id: description
  attributes:
  label: Description
  description: Describe the bug clearly
  validations:
  required: true

- type: textarea
  id: reproduction
  attributes:
  label: Steps to Reproduce
  description: How can we reproduce this bug?
  placeholder: | 1. ... 2. ... 3. ...
  validations:
  required: true

- type: textarea
  id: expected
  attributes:
  label: Expected Behavior
  description: What should happen?
  validations:
  required: true

- type: textarea
  id: actual
  attributes:
  label: Actual Behavior
  description: What actually happens?
  validations:
  required: true

- type: input
  id: environment
  attributes:
  label: Environment
  description: Node version, OS, etc.
  placeholder: "Node 20.x, Windows 11"
