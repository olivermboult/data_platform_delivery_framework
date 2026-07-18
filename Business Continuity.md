# Business Continuity

## Capture Recovery Requirements

**Activities**
- Identify which operational functions or data processes the customer considers business-critical, and document the expected impact of an outage on those operations.
- Capture the customer's recovery time objective and recovery point objective for the systems and data assets in scope.
- Capture whether there are any high availability requirements, such as a minimum uptime threshold, and whether these differ across environments.
- Capture whether service level agreements are in place that define acceptable availability or downtime, and document their terms.
- Identify what the customer expects to be covered by backup and recovery, including data, pipelines, configuration, and reports.
- Review the native backup and recovery capabilities available on the platforms in scope, and document any gaps relative to the stated requirements.

**Outcomes**
- Documented business-critical operational functions and data processes, and the expected impact of an outage on each.
- Documented recovery time objective and recovery point objective for systems and data assets in scope.
- Documented high availability requirements, including any minimum uptime thresholds and differences across environments.
- Documented service level agreements governing acceptable availability or downtime.
- Documented scope of backup and recovery expected by the customer.
- Documented native backup and recovery capabilities available on the platforms in scope, and any gaps relative to stated requirements.

**Pre-requisites**
- Named stakeholders with operational and technical knowledge of the systems in scope are available for a workshop.

**Basis of Estimate**
- Number of systems and data assets in scope
- Complexity of recovery requirements across environments
- Availability of existing SLA or uptime documentation

---

## Identify Business Continuity Arrangements

**Activities**
- Identify whether a formal business continuity plan exists within the customer's organisation, and document whether any new solution would be expected to align with it.
- Identify whether the customer has existing disaster recovery infrastructure or processes, and document whether any new solution would be expected to integrate with them.
- Identify the named owner or team within the customer's organisation responsible for business continuity and disaster recovery.
- Document any regulatory or contractual obligations that govern how quickly systems must be restored following an unplanned outage.
- Identify any dependencies between the systems in scope and other systems or services that could affect recovery in the event of a failure.

**Outcomes**
- Documented business continuity plan in place, including whether the new solution would be expected to align with it.
- Documented existing disaster recovery infrastructure or processes, and whether the new solution would be expected to integrate with them.
- Identified owner or team responsible for business continuity and disaster recovery.
- Documented regulatory or contractual obligations governing system restoration timescales.
- Documented dependencies between systems in scope and other systems or services that could affect recovery.

**Pre-requisites**
- Outputs from the Capture Recovery Requirements task are available.
- A stakeholder with responsibility for business continuity is available for a workshop.

**Basis of Estimate**
- Maturity of the customer's existing business continuity arrangements
- Number of dependencies between systems in scope and other services
- Availability of existing business continuity or disaster recovery documentation

---

## Capture Failover and Testing Requirements

**Activities**
- Capture whether automatic failover is required, or whether manual intervention following a failure is acceptable.
- Capture whether failover requirements apply across all environments or only to production.
- Capture whether disaster recovery testing is expected, and document the expected frequency, scope, and ownership.
- Identify whether existing runbooks or recovery procedures are in place, and capture whether any new solution would be expected to align with them.
- Capture the notification and escalation process in the event of a failure, and identify the roles and individuals who need to be informed.

**Outcomes**
- Documented failover requirements, including whether automatic failover is required or manual intervention is acceptable.
- Documented environments to which failover requirements apply.
- Documented disaster recovery testing requirements, including expected frequency, scope, and ownership.
- Documented existing runbooks or recovery procedures, and whether the new solution would be expected to align with them.
- Documented notification and escalation process in the event of a failure, including individuals and roles to be informed.

**Pre-requisites**
- Outputs from the Identify Business Continuity Arrangements task are available.

**Basis of Estimate**
- Complexity of failover and testing requirements
- Number of environments requiring failover coverage
- Extent of existing runbooks or recovery procedures
