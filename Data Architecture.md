# Data Architecture

## Review the Existing Data Platform

**Activities**
- Document the overall purpose of the existing data platform within the business and its role in supporting data consumers.
- Capture the platform type (cloud, on-premise, or hybrid) and identify the platform manager and their expected involvement in the project.
- Capture the architectural pattern in use, such as a data warehouse or lakehouse.
- Document the existing data layers, their purpose, and how they are separated.
- Identify the key tools and technologies that make up the existing platform, including storage, compute, and orchestration components.
- Capture any naming conventions applied across the platform.
- Document the current environment structure, such as development, test, and production.
- Capture the data retention policies applied within each layer.
- Document the approximate scale of the existing platform, including data volumes and the number of active downstream consumers.
- Identify known issues or limitations with the existing platform that may affect the new solution.
- Identify which elements of the existing platform are expected to be retained, replaced, or extended.

**Outcomes**
- Documented overview of the existing data platform, including architectural pattern, platform type, and overall business purpose.
- Documented data layer structure, including layer names, purposes, and separation approach.
- Documented environment structure across development, test, and production.
- Documented naming conventions currently applied across the platform.
- Documented data retention policies by layer.
- Documented key technologies and tools that make up the existing platform.
- Documented approximate data volumes and number of active downstream consumers.
- Documented known issues and limitations with the existing platform.
- Documented which elements of the platform are expected to be retained, replaced, or extended.
- Identified platform manager and their expected involvement in the project.

**Pre-requisites**
- The customer has an existing data platform in place. This task applies only where a platform exists.
- A technical contact with sufficient knowledge of the current platform is available for a workshop.
- Any existing architecture documentation or platform diagrams are accessible prior to the review.

**Basis of Estimate**
- Complexity and scale of the existing platform
- Availability of existing architecture documentation
- Number of data layers in use
- Number of environments in scope
- Availability of the platform manager for workshop
- Volume and complexity of known issues or technical debt

---

## Review Current Data Flows and Integration Patterns

**Activities**
- Document how data currently moves through the existing platform, from ingestion through to consumption.
- Identify the tools and frameworks used for data movement, transformation, and orchestration within the platform.
- Document the scheduling and trigger patterns that govern data movement, such as batch schedules, event triggers, or manual processes.
- Document any dependencies between pipelines or data flows within the existing platform.
- Identify known performance issues or bottlenecks in current data flows.

**Outcomes**
- Documented overview of current data flow patterns within the existing platform, from ingestion to consumption.
- Identified orchestration and transformation tools currently in use within the platform.
- Documented pipeline scheduling and trigger patterns.
- Documented known pipeline dependencies and downstream impacts.
- Identified performance issues or bottlenecks in current data flows.

**Pre-requisites**
- The customer has an existing data platform in place. This task applies only where a platform exists.
- Outputs from the Review the Existing Data Platform task are available.
- A technical contact with knowledge of existing pipelines and data flows is available for a workshop.

**Basis of Estimate**
- Number and complexity of existing data pipelines
- Availability of pipeline documentation or technical diagrams
- Number of technical contacts required for workshop
- Extent of undocumented processes or informal data movement patterns

---

## Establish Governance and Technical Standards

**Activities**
- Identify whether an internal architecture team or standards body exists, and document any formal review or sign-off processes the solution must go through.
- Identify who holds technical authority on the customer side and who must be involved in architectural decisions.
- Identify any enterprise-wide technology standards the solution must align with.
- Identify any mandated or preferred vendors or platforms at the enterprise level that would constrain architectural choices.
- Identify any documentation requirements for architectural proposals, such as required templates, review boards, or approval workflows.

**Outcomes**
- Identified technical authority holders and key stakeholders required for architectural decisions.
- Documented formal architecture review or sign-off processes that apply to the project.
- Documented enterprise-wide technology standards applicable to the solution.
- Documented mandated or preferred vendors or platforms at the enterprise level.
- Documented documentation requirements for architectural proposals.

**Pre-requisites**
- A named technical authority or architecture lead on the customer side is available for a workshop.

**Basis of Estimate**
- Complexity of the customer's governance and technology standards structure
- Number of stakeholders involved in architecture review processes
- Existence and volume of documented enterprise standards
- Whether formal review processes require written submissions or structured presentations

---

## Capture Architectural Requirements and Constraints

**Activities**
- Identify any constraints from existing infrastructure, licensing agreements, or commercial arrangements that will affect architectural decisions.
- Identify any architectural decisions that have already been made or formally approved, and document which preferences are fixed versus those that remain open.
- Capture the customer's high-level requirements for data layer structure, including which layers are expected and how they should be separated.
- Identify whether data will need to be processed in batch, near-real-time, or a combination of both, and document any specific latency requirements.
- Capture requirements around data retention periods, including whether these differ by layer or data type.
- Identify whether historical data migration is required, and document the scope, data volumes, and expectations around this.
- Capture any naming convention requirements for the new solution, including whether these should follow or extend existing conventions.
- Identify any integration requirements beyond source data ingestion, such as downstream reporting tools, operational system connections, or data sharing arrangements, and document the expected nature of each.
- Identify whether source systems are subject to frequent schema changes, and capture any requirements around how schema drift should be handled.
- Identify any scalability requirements for the new platform, including expected data volume growth and any thresholds for concurrent usage.

**Outcomes**
- Documented infrastructure, licensing, and commercial constraints affecting architectural decisions.
- Documented pre-existing architectural decisions, with fixed and open preferences identified.
- Documented high-level requirements for data layer structure.
- Documented data processing approach requirements, including any latency requirements.
- Documented data retention requirements by layer and data type.
- Documented historical data migration requirements, including scope and volume estimates.
- Documented naming convention requirements for the new solution.
- Documented integration requirements beyond ingestion, including a list of integration points and the expected nature of each.
- Documented schema change handling requirements.
- Documented scalability requirements for the new platform.

**Pre-requisites**
- Named business and technical stakeholders are available for requirements gathering workshops.
- Outputs from the Review the Existing Data Platform task are available where applicable.
- Any existing requirements documentation or project briefs are accessible prior to workshops.

**Basis of Estimate**
- Number of stakeholders required for requirements gathering workshops
- Number of integration points in scope beyond source data ingestion
- Complexity and diversity of processing and latency requirements
- Availability of existing requirements documentation
- Volume of pre-existing architectural decisions requiring review and documentation
- Extent and complexity of historical data migration requirements
