# Development & Deployment

## Capture Source Control Standards and Constraints

**Activities**
- Identify whether the customer has an existing source control platform in place, and document any constraints or preferences regarding its use for the project.
- Capture any existing branching strategies and version control conventions that apply to the customer's source control platform.
- Capture any existing repository structure or naming conventions the project would be expected to follow.
- Identify whether there are any restrictions on where source code can be hosted, such as requirements to remain within a specific cloud region or on-premises environment.

**Outcomes**
- Documented existing source control platform in place, including any constraints or preferences for project use.
- Documented existing branching strategies and version control conventions.
- Documented existing repository structure and naming conventions the project would be expected to follow.
- Documented restrictions on where source code can be hosted.

**Pre-requisites**
- A technical contact with knowledge of source control standards and infrastructure is available for a workshop.

**Basis of Estimate**
- Complexity of existing source control standards and conventions
- Whether hosting restrictions require investigation

---

## Capture Environment Requirements

**Activities**
- Identify and document the environments currently in use across the customer's technical estate, including any used for reporting or data solutions.
- Capture whether environment provisioning is managed through infrastructure as code or through a manual process, and document any constraints or preferences regarding the approach for the project.
- Identify the environments required for the project, such as development, test, UAT, and production.
- Identify whether the required environments already exist or need to be provisioned.
- Identify any performance, scale, or workload requirements that each environment will need to support.
- Identify any constraints on environment availability, such as shared infrastructure or limited capacity, that the project must work within.
- Capture whether non-production environments are expected to reflect the configuration and scale of production, or whether scaled-down alternatives are acceptable.
- Capture the expected data separation between environments and whether production data can be used in lower environments for testing purposes.

**Outcomes**
- Documented existing environments across the customer's technical estate, including those used for reporting or data solutions.
- Documented current approach to environment provisioning and any constraints or preferences for the project.
- Identified environments required for the project.
- Documented whether required environments exist or need to be provisioned.
- Documented performance, scale, and workload requirements for each environment.
- Documented constraints on environment availability.
- Documented expectations for non-production environment configuration relative to production.
- Documented expected data separation between environments and production data usage policy for lower environments.

**Pre-requisites**
- A technical contact with knowledge of the existing environment estate is available for a workshop.

**Basis of Estimate**
- Number of environments required for the project
- Complexity of environment configuration and provisioning requirements
- Extent of constraints on environment availability or data separation

---

## Capture Infrastructure as Code Standards and Requirements

**Activities**
- Identify whether infrastructure as code is in use within the customer's organisation, and document the tooling and languages used, such as Terraform, Bicep, or ARM templates.
- Capture any existing infrastructure as code standards, module structures, or naming conventions the project would be expected to follow.
- Capture whether infrastructure code is stored within the same repository as application code or managed separately, and document any relevant conventions.
- Capture how infrastructure state is managed and stored, including whether a remote state backend is in use and who holds access to it.
- Identify whether existing infrastructure as code modules or templates are available that the project could reuse or would be expected to align with.
- Identify whether any platform policies or governance controls restrict what infrastructure can be provisioned, and document those that apply to the environments in scope.
- Capture the review and approval process for infrastructure changes, and identify whether this differs from the process for application code.
- Capture whether there are any requirements or existing practices around testing or validating infrastructure definitions before they are applied.

**Outcomes**
- Documented infrastructure as code tooling and languages in use, or documented absence of infrastructure as code practices.
- Documented existing infrastructure as code standards, module structures, and naming conventions.
- Documented whether infrastructure code is co-located with application code or managed separately.
- Documented infrastructure state management approach and access arrangements.
- Identified existing modules or templates available for reuse or alignment.
- Documented platform policies or governance controls restricting what infrastructure can be provisioned.
- Documented review and approval process for infrastructure changes.
- Documented requirements or practices around testing or validating infrastructure definitions.

**Pre-requisites**
- Outputs from the Capture Environment Requirements task are available.
- A technical contact with knowledge of infrastructure provisioning practices is available for a workshop.

**Basis of Estimate**
- Maturity of existing infrastructure as code practices
- Complexity of platform policies or governance controls
- Number of existing modules or templates to review

---

## Capture Deployment and Pipeline Requirements

**Activities**
- Identify whether existing CI/CD tooling is in place, and document any constraints or preferences regarding its use for the project.
- Capture whether automated testing is expected as part of the deployment pipeline.
- Capture the expected deployment model, such as automated pipeline-driven deployments or manual promotion between environments.
- Identify any approval or change management processes required before code is promoted between environments.
- Identify whether there are any release windows, change freeze periods, or scheduled maintenance that would affect when deployments can take place.
- Capture whether there are requirements around the ability to roll back deployments or revert to a previous release.
- Capture whether security scanning or compliance checks, such as static analysis or dependency vulnerability scanning, are required as part of the deployment pipeline.
- Capture how secrets, credentials, and configuration values are managed and stored across environments, and document any standards or requirements the project must follow.

**Outcomes**
- Documented existing CI/CD tooling in place, including any constraints or preferences for project use.
- Documented requirements for automated testing within the deployment pipeline.
- Documented expected deployment model.
- Documented approval and change management processes required before code promotion between environments.
- Documented release windows, change freeze periods, or scheduled maintenance affecting deployment timing.
- Documented rollback and revert requirements.
- Documented security scanning and compliance check requirements for the deployment pipeline.
- Documented approach to secrets, credentials, and configuration management across environments.

**Pre-requisites**
- Outputs from the Capture Environment Requirements task are available.

**Basis of Estimate**
- Complexity of existing CI/CD tooling and deployment processes
- Number of approval or change management steps required
- Extent of security scanning or compliance requirements

---

## Identify Development and Deployment Roles and Responsibilities

**Activities**
- Identify who will be responsible for managing deployments and document whether this sits with the customer, the delivery team, or both.
- Identify who holds administrative access to source control and pipeline tooling, and document whether access will need to be provisioned for the delivery team.
- Identify who holds access to the production environment and document whether any access changes will be required during or after delivery.
- Capture the process for requesting and approving access to environments and deployment tooling, and identify who has the authority to grant it.

**Outcomes**
- Identified ownership of deployment management responsibilities across the customer and delivery team.
- Identified administrators of source control and pipeline tooling, and documented access provisioning requirements for the delivery team.
- Identified individuals with access to the production environment and any changes required during or after delivery.
- Documented process for requesting and approving access to environments and deployment tooling, including sign-off authority.

**Pre-requisites**
- Outputs from the Identify Project Stakeholders task are available.

**Basis of Estimate**
- Number of environments and tooling platforms requiring access review
- Complexity of access provisioning processes
