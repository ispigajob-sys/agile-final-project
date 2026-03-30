---
name: Final project
about: issue template for the final project repository
title: ''
labels: ''
assignees: ''

---

**As a** user  
 **I need** the ability to create a product in the catalog  
 **So that** new products can be added  
   
 ### Details and Assumptions
 * The catalog stores all available products
* A product must include at least a name, description, and price
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given I am an authorized user
 When I navigate to the product creation page
 Then the product is successfully created in the catalog
 ```
