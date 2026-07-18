# Platform Migration

## Establish the Migration Scope and Legacy Platform State

**Activities**
- Identify which platforms are being migrated from and to, and document the scope of the migration.
- Document what is currently in use on the legacy platform, including workloads, pipelines, data assets, and reports, and document the overall volume and complexity.
- Identify whether the legacy platform is adequately documented, and capture any areas where additional investigation will be required to understand what exists.
- Identify who owns the legacy platform, and document their availability and willingness to support the project.
- Identify any teams, systems, or processes that depend on the legacy platform, and document the potential impact of the migration on each.

**Outcomes**
- Documented migration scope, including the platforms being migrated from and to.
- Documented inventory of what is currently in use on the legacy platform, including workloads, pipelines, data assets, and reports.
- Documented state of legacy platform documentation and any areas requiring additional investigation.
- Identified legacy platform owner and documented their availability and willingness to support the project.
- Documented teams, systems, and processes dependent on the legacy platform, and the potential impact of the migration on each.

**Pre-requisites**
- Platform migration is confirmed as in scope.
- A technical contact with knowledge of the legacy platform is available for a workshop.

**Basis of Estimate**
- Number and complexity of workloads, pipelines, data assets, and reports on the legacy platform
- Quality and availability of existing legacy platform documentation
- Number of teams or systems dependent on the legacy platform

---

## Capture Migration Requirements and Constraints

**Activities**
- Capture the customer's expectations around which assets will be migrated, rebuilt, or retired as part of the transition.
- Identify any hard deadlines driving the migration, such as contract end dates, licensing renewals, or vendor end-of-life notices.
- Capture whether parallel running of the legacy and new platforms will be required, and document any constraints on its expected duration and associated costs.
- Capture whether the migration must be completed in a single cutover or whether a phased approach is acceptable.
- Capture the customer's expectations around rollback capability in the event that the migration produces unexpected results.
- Capture how the customer will define a successful migration, and identify the criteria they will use to validate the outcome before decommissioning the legacy platform.

**Outcomes**
- Documented customer expectations for which assets will be migrated, rebuilt, or retired.
- Documented hard deadlines driving the migration, including their source and implications.
- Documented requirements and constraints around parallel running of legacy and new platforms.
- Documented cutover approach preference, including whether a phased migration is acceptable.
- Documented rollback expectations in the event of unexpected migration results.
- Documented success criteria and validation approach for the migration.

**Pre-requisites**
- Outputs from the Establish the Migration Scope and Legacy Platform State task are available.

**Basis of Estimate**
- Number of assets to be migrated, rebuilt, or retired
- Complexity of cutover or phasing requirements
- Extent of rollback and parallel running requirements

---

## Identify Migration Risks and Dependencies

**Activities**
- Identify any dependencies between components on the legacy platform that would affect the order in which workloads are migrated.
- Identify any known risks to the migration, such as data quality issues, undocumented integrations, or limited test coverage on legacy workloads.
- Capture the expected approach to user communication during the migration period, and identify any access management requirements during the transition.
- Identify whether any third-party vendors or system owners need to be engaged as part of the migration, and document their roles and any relevant dependencies.
- Identify any data migration requirements, such as the need to move historical data to the new platform, and document the expected scope and any constraints.

**Outcomes**
- Documented dependencies between legacy platform components and any implied migration sequencing requirements.
- Documented known migration risks, including data quality issues, undocumented integrations, or limited test coverage.
- Documented expected approach to user communication during the migration period and identified access management requirements.
- Documented third-party vendors or system owners to be engaged, including their roles and dependencies.
- Documented data migration requirements, including expected scope and constraints.

**Pre-requisites**
- Outputs from the Establish the Migration Scope and Legacy Platform State task are available.

**Basis of Estimate**
- Number and complexity of legacy platform dependencies
- Extent of known risks and undocumented components
- Number of third-party vendors or system owners to engage
