# Data Sources & Ingestion

## Identify Source Systems

**Activities**
- Identify all source systems expected to be in scope for the project.
- Identify any source systems that may be added to scope at a later stage, and document these as provisional.
- For each source system, document its type, hosting location, and whether it is currently active, legacy, or scheduled for replacement.
- Identify the Data Owner, Data Steward, and any relevant data engineers for each source system.
- Identify any source systems that are shared with other teams or business areas, and document any constraints this creates.
- Document the size of each source system, including the number of entities and approximate data volumes.
- Document expected data growth and whether volumes are likely to increase significantly.
- Document any known quality, reliability, or availability concerns for each source system, and document the risk each presents to delivery.

**Outcomes**
- Documented list of source systems in scope, including type, hosting location, and status.
- Documented provisional source systems that may be added to scope at a later stage.
- Identified Data Owner, Data Steward, and relevant data engineers for each source system.
- Documented source systems shared with other teams or business areas, including any constraints this creates.
- Documented size of each source system, including number of entities and approximate data volumes.
- Documented expected data growth and volume projections for each source system.
- Documented known quality, reliability, or availability concerns for each source system, identified as delivery risks.

**Pre-requisites**
- Named stakeholders with knowledge of the organisation's data landscape are available for a workshop.

**Basis of Estimate**
- Number of source systems in scope
- Availability of existing source system documentation
- Number of stakeholders required to identify ownership and contacts
- Extent of known quality or availability concerns

---

## Establish Source System Access and Connectivity

**Activities**
- Identify the access method for each source system and document whether access is achievable at the required scale.
- Identify whether credentials and connection details are available for each source system, and document any formal approvals required, such as data sharing agreements or information governance sign-off.
- Identify who is responsible for granting access to each source system, and document any lead times associated with the access process.
- Document any firewall, network, or infrastructure requirements, such as VPNs, data gateways, or virtual machines.
- Document any instances where access has previously been restricted or declined, and document the risk this presents to delivery.

**Outcomes**
- Documented access method for each source system, including any scalability constraints.
- Documented credential and connection detail availability, and formal approvals required.
- Identified individuals or teams responsible for granting access to each source system, and any associated lead times.
- Documented firewall, network, or infrastructure requirements for each source system.
- Documented any previous instances of restricted or declined access, and associated delivery risks.

**Pre-requisites**
- Outputs from the Identify Source Systems task are available.
- A technical contact with knowledge of network and infrastructure requirements is available for a workshop.

**Basis of Estimate**
- Number of source systems requiring access review
- Complexity of network or infrastructure requirements
- Number of formal approvals or agreements required
- History of access restrictions or complications

---

## Capture Ingestion Requirements

**Activities**
- Capture the expected ingestion frequency for each source system and identify any scheduling constraints.
- Capture the intended ingestion approach for each entity, such as full load, incremental load, or real-time ingestion.
- Identify whether historical data will be required from each source system, document the expected scope, and capture any differences in structure or availability compared to current data.
- Document or obtain a data dictionary for each source system, noting unique keys, incremental columns, and any known anomalies.
- Document any existing data retention or archival policies that apply to each source system, and note the implications for data availability during ingestion.

**Outcomes**
- Documented ingestion frequency and scheduling constraints for each source system.
- Documented intended ingestion approach for each entity.
- Documented historical data requirements for each source system, including scope and any structural differences from current data.
- Documented data dictionaries for each source system, including unique keys, incremental columns, and known anomalies.
- Documented data retention and archival policies for each source system, including implications for data availability during ingestion.

**Pre-requisites**
- Outputs from the Identify Source Systems task are available.
- A technical contact with knowledge of source system structures and data policies is available for a workshop.

**Basis of Estimate**
- Number of source systems and entities in scope
- Availability of existing data dictionaries or technical documentation
- Complexity of ingestion requirements across source systems
- Extent of historical data requirements

---

## Identify Source System Dependencies and Consumers

**Activities**
- Identify existing solutions, processes, or jobs that depend on each source system, such as SQL jobs, integration services, or data pipelines.
- Identify existing reports or analytical outputs that rely on each source system.
- Identify other teams or business areas that depend on each source system, and document any constraints on access or ingestion scheduling this creates.
- Identify any dependencies between source systems themselves, and document any implied sequencing requirements for ingestion.
- Identify the process by which changes to source system structures or schemas will be communicated to the delivery team.

**Outcomes**
- Documented existing solutions, processes, and jobs that depend on each source system.
- Documented existing reports and analytical outputs that rely on each source system.
- Documented teams and business areas that depend on each source system, and any constraints on access or scheduling this creates.
- Documented inter-dependencies between source systems and any implied ingestion sequencing requirements.
- Documented process for communicating source system structure changes to the delivery team.

**Pre-requisites**
- Outputs from the Identify Source Systems task are available.
- Named stakeholders from dependent teams or business areas are available for a workshop.

**Basis of Estimate**
- Number of source systems in scope
- Number of known dependent solutions, processes, or reports
- Complexity of cross-team dependencies
- Extent of inter-dependencies between source systems

---

## Identify Third-Party Source Systems

**Activities**
- Identify any source systems that are hosted or owned by a third party.
- Identify whether the third party will need to be engaged during the project, and at what stage their involvement would be required.
- Document any formal agreements, approvals, or access processes required for each third-party source, and document the timeline and risk associated with securing access.
- Capture any data quality or freshness commitments provided by the third party, and identify any gaps between these commitments and the project requirements.
- Identify any constraints on the format, frequency, or method of data delivery that the third party imposes.

**Outcomes**
- Documented third-party source systems, including their purpose and the data they provide.
- Documented whether third-party engagement will be required and the expected timing.
- Documented formal agreements, approvals, and access processes required for each third-party source.
- Documented timeline and delivery risks associated with securing third-party access.
- Documented third-party data quality and freshness commitments, including any identified gaps.
- Documented constraints on data format, frequency, or delivery method imposed by third parties.

**Pre-requisites**
- Outputs from the Identify Source Systems task are available.
- Existing third-party contracts or data sharing agreements are accessible where available.

**Basis of Estimate**
- Number of third-party source systems in scope
- Complexity of access or approval processes for each third party
- Availability of existing contracts or agreements
- Number of stakeholders required for workshop
