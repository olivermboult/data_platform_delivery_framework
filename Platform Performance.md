# Platform Performance

## Review Current Performance and Known Issues

**Activities**
- Identify any known performance issues or bottlenecks in existing solutions, and document the impact these have had on the business.
- Identify whether any service level agreements are in place, and document any performance obligations the project will be expected to meet.
- Identify any available baseline performance metrics from the existing environment, such as typical data volumes processed, query response times, and refresh frequencies.
- Identify any scheduled jobs or processes outside the data platform that any refresh or processing schedule will need to align with.

**Outcomes**
- Documented known performance issues or bottlenecks in existing solutions, including business impact.
- Documented service level agreements in place and any performance obligations the project will be expected to meet.
- Documented baseline performance metrics from the existing environment, including data volumes, query response times, and refresh frequencies.
- Documented scheduled jobs or processes outside the data platform that refresh or processing schedules must align with.

**Pre-requisites**
- A technical contact with knowledge of existing solution performance is available for a workshop.

**Basis of Estimate**
- Number of known performance issues to review
- Availability of existing performance metrics or documentation
- Number of external scheduled jobs or processes to align with

---

## Capture Performance Requirements

**Activities**
- Capture the expected data volumes for each key entity, and identify any projections or assumptions the customer has regarding how these will grow over time.
- Capture the expected number of concurrent users and identify any peak periods for report consumption or data processing.
- Capture the expected response time for report and query execution, and identify any scenarios where faster response times are particularly important.
- Capture the acceptable latency between source system updates and data being available for consumption, and identify any datasets where near-real-time refresh is required.
- Capture any pipeline completion windows, such as requirements for overnight processing to complete before business hours begin.

**Outcomes**
- Documented expected data volumes for each key entity and any growth projections or assumptions.
- Documented expected number of concurrent users and peak periods for report consumption or data processing.
- Documented expected response time for report and query execution, including any scenarios with specific performance requirements.
- Documented acceptable data latency requirements and any datasets requiring near-real-time refresh.
- Documented pipeline completion window requirements.

**Pre-requisites**
- Outputs from the Review Current Performance and Known Issues task are available.
- Named business and technical stakeholders are available for a workshop.

**Basis of Estimate**
- Number of key entities with distinct volume and growth projections
- Number of report types with specific performance requirements
- Complexity of latency and pipeline window requirements

---

## Identify Performance Monitoring Responsibilities

**Activities**
- Identify who will be responsible for monitoring and responding to performance issues following go-live.
- Identify whether the customer has existing performance benchmarks or baselines, and document what performance expectations the project will be measured against.
- Identify any cost constraints that may limit the capacity available for performance, and capture the customer's tolerance for any trade-off between cost and performance.

**Outcomes**
- Identified individuals or teams responsible for monitoring and responding to performance issues after go-live.
- Documented existing performance benchmarks or baselines and the performance expectations the project will be measured against.
- Documented cost constraints affecting capacity for performance and customer tolerance for cost-performance trade-offs.

**Pre-requisites**
- Outputs from the Capture Performance Requirements task are available.

**Basis of Estimate**
- Complexity of performance monitoring responsibilities
- Availability of existing benchmarks or baselines
