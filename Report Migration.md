# Report Migration

## Establish the Report Migration Scope

**Activities**
- Identify the reporting tool or tools from which reports would be migrated.
- Review the existing report estate, documenting the number of reports, usage patterns, and ownership, and identifying which reports are actively used and which are redundant.
- Identify whether the existing reports are well-documented or whether reverse-engineering will be required to understand what they do, and document the implications for scope and timeline.
- Identify any reports that are embedded in other applications or portals, and document these as requiring additional consideration.

**Outcomes**
- Documented reporting tools from which reports would be migrated.
- Documented existing report estate, including number of reports, usage patterns, ownership, actively used reports, and redundant reports.
- Documented state of existing report documentation and implications for scope and timeline where reverse-engineering will be required.
- Documented reports embedded in other applications or portals.

**Pre-requisites**
- Report migration is confirmed as in scope.
- A stakeholder with knowledge of the existing report estate is available for a workshop.

**Basis of Estimate**
- Number of reports in the existing estate
- Availability of existing report documentation
- Number of embedded reports requiring additional consideration

---

## Capture Report Migration Requirements

**Activities**
- Identify any complex calculation logic or custom measures within existing reports that will need to be translated into the new environment.
- Capture the customer's expectations around what will be migrated, rebuilt, or retired as part of the transition.
- Capture whether parallel running of the legacy and new reporting tools will be required, and document any constraints around its expected duration.
- Capture how the customer expects to validate that migrated reports are equivalent to the originals, and identify the criteria that will define a successful migration.
- Capture the expected approach to user communication when users are transitioned from the legacy tool to the new solution.

**Outcomes**
- Documented complex calculation logic or custom measures within existing reports that will require translation.
- Documented customer expectations for which reports will be migrated, rebuilt, or retired.
- Documented requirements and constraints around parallel running of legacy and new reporting tools.
- Documented validation approach and success criteria for the migration.
- Documented expected approach to user communication during the transition.

**Pre-requisites**
- Outputs from the Establish the Report Migration Scope task are available.

**Basis of Estimate**
- Number of reports to be migrated, rebuilt, or retired
- Complexity of calculation logic or custom measures to translate
- Whether parallel running is required

---

## Identify Migration Risks and Constraints

**Activities**
- Identify any reports considered business-critical that must be available in the new solution before the legacy reporting tool is decommissioned.
- Identify whether existing report owners are available to support the migration and validate that recreated reports meet the original requirements.
- Identify any hard dependencies on the legacy reporting tool from other systems or processes that must be resolved before decommissioning.
- Identify any hard deadlines driving the migration, such as licensing end dates or planned decommissions.

**Outcomes**
- Documented business-critical reports that must be available before the legacy tool is decommissioned.
- Documented availability of existing report owners to support migration and validation.
- Documented hard dependencies on the legacy reporting tool from other systems or processes.
- Documented hard deadlines driving the migration, including their source and implications.

**Pre-requisites**
- Outputs from the Establish the Report Migration Scope task are available.

**Basis of Estimate**
- Number of business-critical reports requiring priority migration
- Number of hard dependencies on the legacy tool
- Complexity of hard deadlines or decommission timelines
