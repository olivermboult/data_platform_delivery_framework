# Data Modelling

## Review the Existing Data Model

**Activities**
- Capture the customer's expectations around whether the new solution should align with, extend, or replace existing models.
- Document the modelling methodology currently in use.
- Document the existing data layers and the modelling approach applied to each.
- Capture existing entity relationships, including cardinality and join paths.
- Document any business logic or metric definitions already applied within the existing model.
- Capture any naming conventions applied to entities and attributes.
- Document any known complexity in the existing model that could affect the scope or timeline of the project.

**Outcomes**
- Documented overview of existing data models, transformation logic, and reporting structures.
- Documented customer expectations around whether the new solution should align with, extend, or replace existing models.
- Documented modelling methodology currently in use.
- Documented modelling approach applied to each data layer.
- Documented existing entity relationships, including cardinality and join paths.
- Documented business logic and metric definitions applied within the existing model.
- Documented naming conventions applied to entities and attributes.
- Documented known complexities in the existing model and their potential impact on scope.

**Pre-requisites**
- The customer has existing data models or transformation logic in place. This task applies only where models exist.
- A technical contact with knowledge of the existing model is available for a workshop.
- Any existing model documentation or data dictionaries are accessible prior to the review.

**Basis of Estimate**
- Number and complexity of existing data models
- Availability of existing model documentation
- Number of entities and relationships to document
- Volume of existing business logic and metric definitions
- Number of data layers with distinct modelling approaches

---

## Capture Modelling Approach and Constraints

**Activities**
- Capture the customer's preferred modelling methodology, such as star schema, data vault, or wide tables, and identify whether this is fixed or open to discussion.
- Identify any constraints or existing practices that should influence the modelling approach.
- Identify which layers in the solution are expected to have a formal data model.
- Identify whether a single shared semantic model is expected or whether multiple models will be required.
- Identify any preferred or mandated tools for data modelling and semantic layer development.
- Identify any documentation requirements for the data model, such as data dictionaries or entity relationship diagrams.

**Outcomes**
- Documented customer preference for modelling methodology, including whether it is fixed or open to discussion.
- Documented constraints and existing practices that should influence the modelling approach.
- Identified which layers in the solution are expected to have a formal data model.
- Identified whether a single shared or multiple semantic models are expected.
- Documented any preferred or mandated tooling for data modelling and semantic layer development.
- Documented documentation requirements for the data model.

**Pre-requisites**
- Outputs from the Review the Existing Data Model task are available where applicable.
- Named technical stakeholders are available for a workshop.

**Basis of Estimate**
- Number of layers expected to have a formal data model
- Complexity of existing constraints or practices
- Number of stakeholders required for workshop

---

## Capture Modelling Requirements

**Activities**
- Identify the key entities and domains that will need to be modelled across the solution.
- Identify the expected grain for key entities within the model, including the level at which data should be stored and queried.
- Capture the key business logic and calculations that must be applied within the model, and identify the stakeholders responsible for validating these.
- Capture any known metric definitions and document any variations in how the business currently calculates them.
- Identify whether historical data tracking will be required, such as slowly changing dimensions or effective dating, and document which entities this applies to.
- Identify the measures, hierarchies, and groupings expected within the semantic layer.

**Outcomes**
- Documented key entities and domains to be modelled across the solution.
- Documented expected grain for key entities within the model.
- Documented key business logic and calculations to be applied within the model, and identified validation stakeholders.
- Documented known metric definitions and any variations in how they are calculated across the business.
- Documented historical data tracking requirements and the entities they apply to.
- Documented expected measures, hierarchies, and groupings within the semantic layer.

**Pre-requisites**
- Named business and technical stakeholders who can define and validate business logic and metric definitions are available for a workshop.
- Outputs from the Review the Existing Data Model task are available where applicable.

**Basis of Estimate**
- Number of key entities and domains to be modelled
- Complexity and volume of business logic and metric definitions
- Number of stakeholders required to validate metric definitions
- Extent of historical data tracking requirements
- Number of measures, hierarchies, and groupings expected in the semantic layer
