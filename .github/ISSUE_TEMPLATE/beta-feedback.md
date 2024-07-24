---
name: Beta Feedback
about: If you have participated in our beta program, you can provide feedback here
title: ''
labels: ''
assignees: ''

---

name: Beta Feedback
description: Provide feedback on the beta version
title: "[BETA FEEDBACK] "
labels: beta, feedback
assignees: ''

body:
- type: markdown
  attributes:
    value: "Please provide the following details to give feedback on the beta version."

- type: input
  id: beta-version
  attributes:
    label: Beta Version
    description: Specify the beta version you are testing.
    placeholder: "e.g., v1.2.3-beta"

- type: textarea
  id: feedback
  attributes:
    label: Feedback
    description: Describe your feedback on the beta features.
    placeholder: "Describe your feedback."

- type: textarea
  id: suggestions
  attributes:
    label: Suggestions
    description: Provide any suggestions you have for improvement.
    placeholder: "Describe your suggestions."

- type: textarea
  id: additional-comments
  attributes:
    label: Additional Comments
    description: Add any other comments here.
    placeholder: "Any other comments."
