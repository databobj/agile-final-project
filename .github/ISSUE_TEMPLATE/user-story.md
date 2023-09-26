---
name: User Story
about: The template for creating user stories.
title: ''
labels: ''
assignees: ''

---

**As a** Service Provider
 **I need**  to deploy the service to the cloud
 **So that** I can scale capacity with user demand
   
 ### Details and Assumptions
 * We will use IBM Cloud
 * Deploy as a Cloud Foundary app
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given I have deployed to the cloud
 When a customer comes to our URL
 Then our service will be available
 ```
