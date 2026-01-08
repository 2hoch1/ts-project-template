name: Feature Request
description: Suggest a new feature
title: "[Feature] "
labels: ["enhancement"]

body:

- type: markdown
  attributes:
  value: Have an idea? Share it with us!

- type: textarea
  id: description
  attributes:
  label: Description
  description: Describe the feature you'd like
  validations:
  required: true

- type: textarea
  id: motivation
  attributes:
  label: Motivation
  description: Why would this feature be useful?
  validations:
  required: true

- type: textarea
  id: alternatives
  attributes:
  label: Alternatives Considered
  description: Any alternatives?
