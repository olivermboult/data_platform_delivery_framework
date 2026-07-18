# Customer Data Engineer

The Customer Data Engineer is a technical member of the customer's internal data or IT team who works hands on with the customer's existing data infrastructure day to day. They are the primary source of technical implementation detail throughout Discovery, providing the granular knowledge of existing pipelines, source system configuration, and deployment practices that the Technical Stakeholder is not expected to hold. The delivery team will typically engage the Technical Stakeholder for high level technical direction and the Customer Data Engineer separately for implementation detail, though both may attend the same sessions where the subject matter warrants it. There may be multiple Customer Data Engineers on a project, each covering different systems or technical domains.

**Framework Involvement**

Discovery
- Provides technical detail on existing pipelines and jobs running against source systems during Platform Discovery and Source System Discovery, including their purpose, frequency, and current reliability.
- Provides detail on existing source system configuration, access arrangements, and any known constraints or issues that may affect ingestion design decisions.
- Contributes technical detail on existing deployment practices, source control usage, and environment structure during Operating Model Discovery.
- Supports the delivery team in obtaining or producing data dictionaries and technical documentation for source systems where these do not already exist.
- Identifies any firewall rules, network requirements, or access restrictions that must be resolved before source system connectivity can be established.

Design
- Remains available to the Data Engineer and I&S Engineer throughout Design to clarify technical implementation detail and validate design decisions against the realities of the existing environment.
- Confirms that source system connection dependencies, including firewall rules and network requirements, are accurately documented in the Design before build begins.

Platform
- Supports the Data Engineer with source system connectivity during the Platform phase, assisting with access provisioning, firewall changes, and any network configuration required to establish connections to source systems.
- Confirms that access to all source systems required for ingestion has been provisioned and is available to the delivery team before the platform readiness note is produced.

Delivery
- Where the project is built collaboratively, works alongside the Data Engineer throughout the Platform and Build phases, contributing to the build under the oversight of the Data Lead.

Live
- Attends knowledge transfer sessions at the close of the project, reviewing documentation produced by the delivery team and building familiarity with the solution before responsibility transfers to the customer's internal team.
- Confirms that the knowledge transfer outputs are sufficient to support the customer's internal team in operating and maintaining the solution independently.