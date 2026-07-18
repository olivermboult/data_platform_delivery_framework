# Monitoring & Alerting

## Review Existing Monitoring and Alerting

**Activities**
- Identify the tools and platforms the customer currently uses for monitoring, logging, and alerting, and document any constraints or preferences regarding their use for the project.
- Identify any known gaps in the customer's current monitoring, logging, or alerting coverage.
- Identify whether existing monitoring tools integrate with incident management, ticketing, or notification systems, and document any relevant details.

**Outcomes**
- Documented tools and platforms currently used for monitoring, logging, and alerting, including any constraints or preferences for project use.
- Documented known gaps in current monitoring, logging, or alerting coverage.
- Documented integrations between existing monitoring tools and incident management, ticketing, or notification systems.

**Pre-requisites**
- A technical contact with knowledge of the existing monitoring and alerting estate is available for a workshop.

**Basis of Estimate**
- Number of monitoring tools currently in use
- Complexity of existing integrations with incident or notification systems
- Extent of known coverage gaps

---

## Capture Monitoring Requirements

**Activities**
- Identify the categories of events the customer expects to be logged across the platform and data layers, such as pipeline runs, user activity, and system errors.
- Capture whether pipeline monitoring is required, covering success, failure, duration, and data volumes processed.
- Capture whether data freshness monitoring is required, and identify which datasets or pipelines should be monitored and at what frequency.
- Capture whether data quality alerting is required as part of the monitoring scope, and identify the conditions or thresholds that should trigger an alert.
- Capture whether security and access monitoring is required, such as alerting on unusual access patterns or activity outside expected hours.
- Capture whether infrastructure or resource monitoring is required, such as tracking compute usage, memory, or storage capacity.
- Capture whether service level objectives or performance baselines exist that monitoring should be designed to track.
- Capture whether a centralised monitoring dashboard is required, and identify the intended audience.

**Outcomes**
- Documented event categories expected to be logged across the platform and data layers.
- Documented pipeline monitoring requirements, including metrics and triggers.
- Documented data freshness monitoring requirements, including datasets and frequencies.
- Documented data quality alerting requirements, including conditions and thresholds.
- Documented security and access monitoring requirements.
- Documented infrastructure and resource monitoring requirements.
- Documented service level objectives or performance baselines that monitoring should track.
- Documented requirements for a centralised monitoring dashboard, including intended audience.

**Pre-requisites**
- Outputs from the Review Existing Monitoring and Alerting task are available.
- Named technical and operational stakeholders are available for a workshop.

**Basis of Estimate**
- Number of platform and data layers requiring monitoring
- Breadth of monitoring categories in scope
- Complexity of service level or performance baseline requirements

---

## Capture Alerting and Notification Requirements

**Activities**
- Capture who should receive alerts, by what method, and under what conditions.
- Capture whether out-of-hours alerting is required, and identify the individuals or teams who should be notified.
- Capture whether the customer uses alert severity levels or priority tiers, and document any existing frameworks or conventions the project should align with.
- Capture whether alerts should integrate with an existing incident management or ticketing system, and identify which system is in use.
- Capture whether cost monitoring and alerting are required, and identify any budget thresholds the customer expects to be notified about.

**Outcomes**
- Documented alert recipients, notification methods, and triggering conditions.
- Documented out-of-hours alerting requirements and identified individuals or teams to be notified.
- Documented alert severity levels or priority tiers in use and any frameworks the project should align with.
- Documented requirements for incident management or ticketing system integration, and identified target system.
- Documented cost monitoring and alerting requirements, including budget thresholds.

**Pre-requisites**
- Outputs from the Capture Monitoring Requirements task are available.

**Basis of Estimate**
- Number of alert categories and recipient groups
- Complexity of incident management or ticketing system integration
- Whether cost alerting requirements are in scope

---

## Capture Log Retention Requirements

**Activities**
- Capture the retention period the customer requires for logs, and identify any compliance or regulatory obligations that govern how long logs must be retained.
- Capture whether different categories of logs have different retention requirements, and document any distinctions.
- Capture whether log data will need to be accessible to support compliance audits or security investigations, and document any requirements around format or access.

**Outcomes**
- Documented log retention periods and any compliance or regulatory obligations governing them.
- Documented retention requirements by log category, including any distinctions between categories.
- Documented requirements for log accessibility to support compliance audits or security investigations, including format and access requirements.

**Pre-requisites**
- Outputs from the Capture Monitoring Requirements task are available.
- Outputs from the Identify Regulatory and Compliance Obligations task are available where applicable.

**Basis of Estimate**
- Number of log categories with distinct retention requirements
- Complexity of compliance or regulatory obligations governing log retention
