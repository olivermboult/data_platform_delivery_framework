# Data Steward

The Data Steward is an operational representative on the customer side responsible for the day to day management and quality of data within a specific domain. Where the Data Owner holds ultimate accountability, the Data Steward acts as the custodian of the data in practice, ensuring it is accurate, well documented, consistently classified, and accessible to those who need it. The Data Steward typically works closely with the delivery team during Discovery and Build, providing the detailed knowledge of data structure, quality, and behaviour that underpins design and build decisions.

**Framework Involvement**

Discovery
- Acts as the primary source of detailed knowledge on data structure, quality, and behaviour within their domain during Source System Discovery and Business-Data Alignment sessions.
- Provides data dictionaries, metadata, and documentation for source systems within their domain, or supports the delivery team in producing these where they do not exist.
- Identifies and documents known data quality issues, inconsistencies, and gaps within their domain, including any historical issues that may affect trend analysis or reporting outputs.
- Confirms data classifications, definitions, and standards that apply within their domain and ensures these are reflected in the solution design.
- Contributes to the definition of data quality rules and thresholds the solution must meet within their domain.
- Supports the delivery team in understanding data lineage within their domain, including how data flows between systems and how it has been transformed or modified historically.

Design
- Reviews and approves source to target mappings for entities within their domain, confirming that transformation logic and business rules accurately reflect how data should be structured and used.
- Validates data modelling decisions affecting their domain, including grain, calculated fields, and business logic applied within the silver and gold layers.
- Confirms that data quality rules and thresholds defined during Discovery are accurately reflected in the Design before build begins.

Build
- Remains available to the Data Engineer throughout Build to clarify data structure, business rules, and transformation logic within their domain.
- Validates transformation outputs against source data and business expectations where queries arise during build.
- Confirms that transformation logic and business rules applied within the solution accurately reflect how data should behave within their domain before the development completion note is produced.

Quality Assurance
- Confirms that data outputs within their domain meet the agreed quality thresholds before the solution proceeds to release.

Live
- Participates in the post project review, providing input on whether data quality and stewardship arrangements have operated effectively throughout the engagement.