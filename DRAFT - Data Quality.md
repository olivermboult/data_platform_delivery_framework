# Design - Data Quality

## Quality Rules and Checks

- Define the data quality rules and thresholds to be applied to each entity in scope, covering dimensions such as completeness, accuracy, consistency, and duplication, and confirm these with the relevant Data Owners and Data Stewards before build begins.
- Define the data quality checks to be applied at each layer of the pipeline, specifying what is checked, where, and what action is taken on failure.
- Document how known and accepted data quality issues identified during Discovery will be handled within the pipeline, confirming whether they are flagged, passed through, or escalated for resolution.

## Failure Handling and Matching

- Document the approach to quarantining or handling records that fail quality checks, confirming whether they are rejected, flagged, or passed through with a quality indicator.
- Where probabilistic matching or master data management was agreed during Discovery, define the matching rules, confidence thresholds, and how matched and unmatched records are handled within the pipeline.

## Monitoring and Visibility

- Where a data quality monitoring framework was agreed during Discovery, design the framework, including the metrics tracked, the reporting approach, and the alerting thresholds.
- Where end-user visibility of data quality status was agreed during Discovery, define how this will be implemented within the solution, such as through flags, indicators, or a dedicated quality view.
