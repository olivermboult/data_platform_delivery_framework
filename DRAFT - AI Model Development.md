# Design - AI Model Development

## Model Development Specification

- Confirm the use cases and business problems identified during Discovery, and produce a model development specification for each that covers feature selection, training methodology, and validation strategy.
- Specify the data required to train, validate, and test each model, confirming the sources, volumes, and freshness requirements agreed during Discovery.
- Document the approach to training data labelling for supervised learning use cases, including who is responsible, the tooling to be used, and quality assurance steps.
- Confirm the baseline performance established during Discovery and document it as the benchmark against which model outputs will be assessed.

## Evaluation Framework

- Define the model evaluation framework for each use case, specifying the metrics, thresholds, and testing approach that will govern sign-off before a model is approved for production deployment.
- Specify any constraints on model inputs or outputs confirmed during Discovery, such as restrictions on which variables can be used or requirements around explainability, and define how these will be enforced in the build.
- Document the computational and infrastructure requirements for model training and inference, confirming alignment with the infrastructure design.

## Model Drift and Retraining

- Define the approach to handling model drift, specifying the metrics to be monitored, the thresholds that will trigger a review or retrain, and who holds authority to approve a retrain.
- Confirm the retraining frequency and trigger conditions agreed during Discovery, and document these in the model specification.

## Model Documentation and Transition

- Define the model documentation standard, specifying what must be recorded for each model to support auditability, reproducibility, and future maintenance.
- Confirm the dependencies between AI use cases identified during Discovery, and ensure the development sequence is reflected in the Delivery Plan.
- Confirm which existing models or analytical approaches will be replaced and document the transition approach, including how downstream dependencies will be managed during the changeover.
