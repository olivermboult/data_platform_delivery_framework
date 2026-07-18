# Design - MLOps & Model Management

## MLOps Architecture

- Confirm whether the customer's existing MLOps tooling and practices identified during Discovery are suitable for the new solution, and define the MLOps architecture, covering model versioning, deployment pipelines, monitoring, and retraining processes.
- Confirm alignment between the MLOps architecture and the broader environment strategy and deployment pipeline design confirmed during Platform Design.

## Model Deployment and Versioning

- Define how models will be packaged and deployed to production, and specify the validation gates that must be passed before a model is promoted from development through to production.
- Confirm whether a model registry is required, as identified during Discovery, and specify its design, including how model versions will be tracked and who is responsible for managing it.
- Confirm whether rollback capability is required and specify the process for reverting to a previous model version in the event of performance failure.

## Monitoring and Retraining

- Define the monitoring approach for models in production, specifying the metrics tracked, the alerting thresholds, and the process for responding to performance degradation.
- Confirm requirements for data drift and concept drift detection identified during Discovery, and specify the tooling, alerting approach, and responsibilities for reviewing and acting on alerts.
- Confirm the retraining schedule and process for each model, including who is responsible for triggering and approving retrains and how the retrained model is validated before it replaces the current version.

## Lifecycle, Governance, and Dependencies

- Confirm whether experiment tracking and reproducibility are required, as identified during Discovery, and specify what records will be maintained and how they will be stored.
- Confirm the audit trail requirements identified during Discovery, including the scope of records to be retained and the retention period.
- Confirm the process for retiring a model from production, including how downstream dependencies will be managed and how decommissioning will be documented.
- Confirm any dependencies between the model lifecycle and the broader data platform, such as retraining pipelines that rely on refreshed source data, and ensure these are reflected in the pipeline design.
