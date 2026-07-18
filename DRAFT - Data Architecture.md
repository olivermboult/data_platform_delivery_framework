# Design - Data Architecture

## Architecture Design

- Produce a detailed architecture diagram documenting all layers, workspaces, data flows, and integration points across the full solution.
- Define the physical structure of each data layer, including workspace layout, schema or lakehouse separation, and the location and purpose of each object type.
- Confirm the naming conventions to be applied across all layers, objects, and workspaces, in line with any conventions identified during Discovery.
- Define the data retention design for each layer, specifying how retention periods will be implemented and whether these differ by layer or data type.

## Data Flow and Processing

- Define the ingestion approach for each data source, specifying whether data will be processed in batch, near-real-time, or a combination of both, and confirming the expected latency for each.
- Confirm how historical data will be handled within the architecture, including whether a full historical load is required and how this affects the layer design and ingestion approach.
- Define the approach to schema evolution, confirming how changes to source system structures will be detected and handled within the pipeline without disrupting downstream layers.

## Integration and Standards

- Document the integration design for each tool or system identified during Discovery as requiring a connection to the data platform, confirming the connection method and any dependencies on the broader infrastructure design.
- Confirm that the completed architecture has been reviewed and approved by any internal architecture team or standards body identified during Discovery before build begins.
