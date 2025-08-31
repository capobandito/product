name: "📦 Epic"
description: "Create an Epic (group of related tasks)"
title: "Epic: <short name>"
labels: ["type: epic"]
body:
  - type: markdown
    attributes:
      value: |
        ## 📦 Epic
        Use this template to describe a deliverable that groups related tasks and stories.

  - type: input
    id: owner
    attributes:
      label: Owner
      description: Who is responsible for driving this Epic?
      placeholder: "@username"

  - type: textarea
    id: goal
    attributes:
      label: Goal
      description: What’s the outcome this Epic should achieve?
      placeholder: |
        - State the problem or opportunity
        - Explain the desired outcome

  - type: textarea
    id: deliverables
    attributes:
      label: Deliverables
      description: What concrete outputs or components will this Epic deliver?
      placeholder: |
        - Deliverable 1
        - Deliverable 2

  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance Criteria
      description: When is this Epic considered complete?
      placeholder: |
        - Criteria 1
        - Criteria 2

  - type: textarea
    id: tasks
    attributes:
      label: Linked Tasks / Stories
      description: Break this Epic down into tasks or stories (link issue numbers)
      placeholder: |
        - #123 Task: Implement backend service
        - #124 Task: Build frontend UI

  - type: textarea
    id: related
    attributes:
      label: Related Initiative
      description: Link the Initiative this Epic contributes to
      placeholder: "#456 Initiative: Fraud Detection Platform"
