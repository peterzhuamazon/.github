---
name: '❔ GitHub Request'
about: 'Request an update to permissions/management/settings on the opensearch-project GitHub organization or its repositories.'
title: '[GitHub Request]'
labels: 'github-request'
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to submit GitHub Requset! Please note that the estimate time for the request to be resolved is 7-10 days from the time of the request.
   - type: dropdown
    attributes:
      description: 'What is the type of request?'
      multiple: false
      options:
        - # Empty first option to force selection
        - User Permission
        - Organization Membership
        - Repository Management
        - Settings Update
        - Secret Update
        - GitHub Action
        - Other
    validations:
      required: true
  - type: textarea
    attributes:
      description: 'Detail of the request'
    value: |
      _Describe the actions you are requesting (e.g., GitHub Actions in the`<repository> take too long to allocate runners)._
      _If this is about a repository, please contact the corresponding maintainers before raising the issue._
    validations:
      required: true
  - type: textarea
    attributes:
      description: 'Additional information to support your request'
    value: |
      _Provide reasons for your request._
      _For example, if you request to add a new maintainer, confirm you followed the steps in the [Becoming a Maintainer](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#becoming-a-maintainer) guide._
    validations:
      required: true
  - type: textarea
    attributes:
      description: 'When does this request need to be completed?'
    value: |
      _Requests typically require 7-10 business days to process. Specify your request timeline and whether or not it is an urgent request._
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        _Track the progress of your request here: https://github.com/orgs/opensearch-project/projects/208/views/33_  
        _Member of @opensearch-project/admin will take a look at the request soon._
        _Thanks!_