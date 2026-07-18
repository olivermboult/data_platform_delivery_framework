# Data Quality

## Establish the Existing Data Quality Position

**Activities**
- Identify whether the customer has an existing data quality framework or set of standards, and document its scope and how it applies to the data in scope for this project.
- Capture the customer's existing understanding of their data quality position, whether through formal assessments or stakeholder knowledge.
- Identify whether any data quality profiling or monitoring has been carried out on the data in scope, and capture the results where available.
- Identify whether any data quality issues have previously caused business problems, and document the impact these had.
- Capture the data quality position across key entities, engaging Data Owners, Data Stewards, and Subject Matter Experts, and covering dimensions such as completeness, accuracy, consistency, and duplication.
- Document known and accepted data quality issues and those that must be resolved as part of or prior to the solution.
- Document any historical data quality issues that may affect the reliability of trend analysis or reporting.

**Outcomes**
- Documented data quality framework or standards in place, including scope and applicability to the project.
- Documented overview of the customer's current data quality position, including findings from any formal assessments.
- Documented results of any data quality profiling or monitoring carried out prior to the project.
- Documented data quality issues that have previously caused business problems and their impact.
- Documented data quality findings across key entities, covering completeness, accuracy, consistency, and duplication.
- Documented known and accepted data quality issues and those requiring resolution.
- Documented historical data quality issues that may affect trend analysis or reporting.

**Pre-requisites**
- Outputs from the Identify Data Domains and Ownership Responsibilities task are available.
- Data Owners, Data Stewards, and Subject Matter Experts are available for a workshop.

**Basis of Estimate**
- Number of key entities to review
- Maturity of the customer's existing data quality framework
- Availability of existing data quality assessments or profiling results
- Number of stakeholders required for workshop

---

## Identify Master Data and Matching Requirements

**Activities**
- Identify whether source systems share common identifiers that can be used to join data reliably across systems.
- Identify whether master data management or probabilistic matching will be required, and document the data domains this would affect.
- Identify whether golden record management, deduplication, or entity resolution will be required, and document the domains and source systems involved.

**Outcomes**
- Documented findings on whether source systems share common identifiers for reliable cross-system joins.
- Documented master data management and matching requirements, including affected data domains.
- Documented golden record, deduplication, and entity resolution requirements, including affected domains and source systems.

**Pre-requisites**
- Outputs from the Establish the Existing Data Quality Position task are available.
- A technical contact with knowledge of source system structures and identifiers is available for a workshop.

**Basis of Estimate**
- Number of source systems with potentially overlapping data
- Complexity of identifier structures across source systems
- Scale of duplication or matching requirements

---

## Capture Data Quality Requirements

**Activities**
- Identify whether data quality remediation is in scope, or whether the solution is expected to work around known issues.
- Identify the data quality thresholds and rules the solution must meet, and document the stakeholders responsible for validating these.
- Identify whether a data quality monitoring framework is expected as part of the solution, and document which data domains and quality dimensions it should cover.
- Identify whether data quality status should be visible to end users within the solution, such as through flags, indicators, or a dedicated quality view.
- Identify whether any existing data quality tooling or solution will be retained, integrated with, or replaced as part of the project.

**Outcomes**
- Documented whether data quality remediation is in scope or whether the solution should work around known issues.
- Documented data quality thresholds and rules the solution must meet, and identified validation stakeholders.
- Documented data quality monitoring framework requirements, including the domains and quality dimensions to be covered.
- Documented requirements for data quality visibility within the solution, including expected format where specified.
- Documented the intended treatment of any existing data quality tooling, whether retained, integrated with, or replaced.

**Pre-requisites**
- Outputs from the Establish the Existing Data Quality Position task are available.
- Named business and technical stakeholders responsible for data quality are available for a workshop.

**Basis of Estimate**
- Number of data domains in scope for quality requirements
- Complexity of data quality thresholds and rules
- Number of stakeholders required for workshop
- Whether existing data quality tooling needs to be reviewed
