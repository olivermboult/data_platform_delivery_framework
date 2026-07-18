# Design - Data Modelling

## Mappings and Transformations

- Produce a bronze to silver mapping table, or equivalent, detailing each column of each entity in the silver layer and how it is derived from the bronze layer. Obtain approval from the relevant Data Owner or Data Steward before build begins.
- Produce a silver to gold mapping table, or equivalent, detailing each column of each entity in the gold layer and how it is derived from the silver layer. Obtain approval from the relevant Data Owner or Data Steward before build begins.
- Document the approach to handling nulls, defaults, and unexpected values within transformations, confirming these are applied consistently across all entities in the model.
- Confirm the approach to historical data tracking, such as slowly changing dimensions or effective dating, for each entity where this was identified as a requirement during Discovery, specifying the type and mechanism to be applied.
- Resolve any variations in metric definitions identified during Discovery and document the agreed single definition for each metric, confirmed with the relevant stakeholders before build begins.
- Identify any reusable transformation logic that should be centralised, such as shared date dimensions, common aggregations, or standard business rules, to avoid duplication across use cases.

## Semantic Layer

- Define the semantic layer design, confirming which measures, hierarchies, and relationships will be defined at this layer and how these align with the reporting requirements confirmed during Discovery.
- Confirm whether a single shared semantic model or multiple models will be implemented, and document the structure and scope of each.

## Standards, Validation, and Risks

- Confirm the naming conventions to be applied to all entities, columns, and measures within the model and document these for reference throughout build.
- Confirm the approach to testing data model transformations and define how outputs will be validated against source data and business expectations before the Build phase closes.
- Document any known risks or uncertainties in the transformation logic that could not be fully resolved during Design, and confirm the agreed approach for resolving them during Build.
