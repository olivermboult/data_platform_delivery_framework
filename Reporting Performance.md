# Reporting Performance

## Review Existing Reporting Performance

**Activities**
- Identify any known performance issues with the existing reporting environment and document the impact these have had on user adoption.
- Identify whether any existing benchmarks or load time standards apply that the new solution must match or improve upon.

**Outcomes**
- Documented known performance issues with the existing reporting environment, including impact on user adoption.
- Documented existing benchmarks or load time standards the new solution must match or improve upon.

**Pre-requisites**
- A stakeholder with knowledge of existing reporting performance is available for a workshop.

**Basis of Estimate**
- Number of known performance issues to document
- Availability of existing benchmarks or standards

---

## Capture Reporting Performance Requirements

**Activities**
- Capture the expected report load time for each report type, and identify any scenarios where faster load times are particularly important.
- Capture whether any reports are expected to query large datasets or involve complex calculations, and document these for additional attention during design.
- Capture the customer's expectations around data freshness versus performance, and identify any reports where near-real-time data is a firm requirement rather than a preference.
- Capture whether report caching or pre-aggregation is expected, and identify which reports or datasets the customer expects to benefit from it.
- Capture whether performance testing will be required as part of delivery, and identify the acceptance criteria the solution must meet.

**Outcomes**
- Documented expected report load times by report type, including any scenarios with specific performance requirements.
- Documented reports expected to query large datasets or involve complex calculations.
- Documented customer expectations around data freshness versus performance, including any reports with firm near-real-time requirements.
- Documented caching or pre-aggregation requirements, including the reports or datasets expected to benefit.
- Documented performance testing requirements and acceptance criteria.

**Pre-requisites**
- Outputs from the Review Existing Reporting Performance task are available.
- Named business and technical stakeholders are available for a workshop.

**Basis of Estimate**
- Number of report types with distinct performance requirements
- Complexity of data freshness and caching requirements
- Whether performance testing is in scope

---

## Identify Reporting Performance Responsibilities

**Activities**
- Identify who will be responsible for monitoring and responding to reporting performance issues once the solution is in production.
- Identify any network, device, or connectivity constraints that may affect perceived report performance for specific user groups.

**Outcomes**
- Identified individuals or teams responsible for monitoring and responding to reporting performance issues after go-live.
- Documented network, device, or connectivity constraints that may affect perceived performance for specific user groups.

**Pre-requisites**
- Outputs from the Capture Reporting Performance Requirements task are available.

**Basis of Estimate**
- Complexity of performance monitoring responsibilities
- Number of user groups with distinct connectivity or device constraints
