# Design - Data Sources

## Source to Bronze Mapping

- Confirm that a complete data dictionary is available for each source entity in scope, covering unique keys, incremental columns, and any known anomalies, and resolve any gaps before mapping begins.
- Produce a source to bronze mapping table, or equivalent, detailing each column of each entity in the bronze layer and how it is derived from the source.
- Confirm the mapping has been reviewed and signed off by the relevant Data Owner or Data Steward before build begins.

## Ingestion Design

- Design the load approach for each source entity, covering inserts, updates, deletes, retention, and archival handling.
- Confirm the approach to historical data loading for each source, specifying the scope, the load mechanism, and how any structural differences between historical and current data will be handled.
- Define the pipeline run schedule for each source entity and confirm this aligns with the service level agreements agreed during Platform Design.
- Define the approach to late-arriving or out-of-order data, confirming how these cases will be detected and handled within the pipeline.
- Define the error handling approach for each ingestion pipeline, detailing how failures are detected, logged, and surfaced for resolution.

## Access and Dependencies

- Confirm that credentials and access for each source system are in place and tested before build begins, including any formal approvals, data sharing agreements, or information governance sign-off required.
- Confirm that all connection dependencies, such as firewall rules, VPN configurations, and data gateways, are resolved and in place before build begins.
- Confirm that any third-party source systems have the necessary access agreements in place and that the relevant third parties are engaged and available before build begins.
