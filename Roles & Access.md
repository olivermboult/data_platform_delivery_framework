# Roles & Access

## Review the Existing Access Model

**Activities**
- Document how access to the existing solution is currently managed, including the tools, identity providers, and processes in use.
- Identify any known pain points or gaps in the current access model.
- Capture whether access is expected to be managed through the platform natively, through an identity provider such as Microsoft Entra ID, or through a combination of both.

**Outcomes**
- Documented existing access management approach, including tools, identity providers, and processes in use.
- Documented known pain points and gaps in the current access model.
- Documented expected access management approach for the new solution.

**Pre-requisites**
- A technical contact with knowledge of the existing access model is available for a workshop.

**Basis of Estimate**
- Complexity of the existing access model
- Number of identity providers and tools in use

---

## Capture User Access Requirements

**Activities**
- Identify who will need access to the solution, covering platform administration, data access, and report consumption, and capture their requirements.
- Capture the level of data access required for different groups of users, and identify any datasets or areas that should be restricted to specific individuals or roles.
- Identify any row-level or object-level security requirements driven by the business use cases or data sensitivity.
- Capture whether guest or external user access will be required, and identify any constraints this creates.
- Capture whether multi-factor authentication is required or already enforced across the organisation.
- Capture whether there are any network or location-based access restrictions, such as VPN requirements or IP allowlisting.

**Outcomes**
- Documented user groups requiring access to the solution, including platform administration, data access, and report consumption, and their access requirements.
- Documented data access levels required for different user groups, including any restricted datasets or areas.
- Documented row-level or object-level security requirements and the use cases or data sensitivity driving them.
- Documented guest or external user access requirements and any constraints they create.
- Documented multi-factor authentication requirements or existing enforcement.
- Documented network or location-based access restrictions.

**Pre-requisites**
- Outputs from the Review the Existing Access Model task are available.
- Named stakeholders representing key user groups are available for a workshop.

**Basis of Estimate**
- Number of distinct user groups requiring access
- Complexity of data restriction and security requirements
- Whether external or guest access is in scope

---

## Capture Access Governance Requirements

**Activities**
- Capture the process for requesting, approving, and provisioning access to the solution, and identify who holds authority to grant access.
- Capture how users will be onboarded and offboarded from the solution, and identify whether this integrates with an existing joiner-mover-leaver process.
- Identify any existing access review or recertification processes the customer follows, and capture whether these will apply to the new solution.
- Capture whether privileged or administrative access requires any additional controls or approval processes.
- Capture whether access activity is currently logged or audited, and identify any requirements around access audit trails.

**Outcomes**
- Documented access request, approval, and provisioning process, including access grant authority.
- Documented user onboarding and offboarding process, including any integration with existing joiner-mover-leaver processes.
- Documented existing access review or recertification processes and whether they will apply to the new solution.
- Documented controls and approval processes required for privileged or administrative access.
- Documented access activity logging and audit requirements.

**Pre-requisites**
- Outputs from the Capture User Access Requirements task are available.

**Basis of Estimate**
- Complexity of access governance processes
- Whether joiner-mover-leaver integration is required
- Extent of access audit or logging requirements

---

## Capture Technical and Automated Access Requirements

**Activities**
- Capture whether service principal or automated access will be required for pipelines and deployments, and document how these will be managed and reviewed.
- Capture whether shared service accounts are currently in use in the existing environment, and identify whether the customer has any requirements or restrictions on their use.

**Outcomes**
- Documented requirements for service principal or automated access, including management and review arrangements.
- Documented use of shared service accounts in the existing environment and any customer requirements or restrictions on their use.

**Pre-requisites**
- Outputs from the Capture User Access Requirements task are available.

**Basis of Estimate**
- Number of pipelines or deployments requiring automated access
- Extent of existing shared service account usage
