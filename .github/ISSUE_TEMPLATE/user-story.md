---
name: User Story
about: This template defines a user story
title: ''
labels: ''
assignees: ''

---

**As a** new user
**I need** a registration page
**So that** I can create an account and participate in giving away or acquiring household items.

### Details and Assumptions
* Users should be able to register using their email address, username, and password.
* The system should verify that the email address is not already in use.

### Acceptance Criteria
```gherkin
Given the user is on the registration page
When the user enters a unique email address, username, and password and submits the form
Then the user's account is created, and they are redirected to the login page.
