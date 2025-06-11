# OpenSearch Observability Technical Advisory Group (TAG) Governance Charter

### Purpose

The OpenSearch Project proposes to create a Observability Interest Group that focuses on observability using OpenSearch. This includes log analytics, traces, metrics using OpenSearch and related projects such as Prometheus, OpenTelemetry. This group will also establish guidelines for members, set architecture guidelines, and come up with recommendations which will then be reviewed by TSC for decision making. The group will provide feedback to the TSC before the final decision is made through voting of TSC members.

### Responsibilities

The following is a non-exhaustive sample list of activities and deliverables that are in-scope for this SIG

* Drive feature development and enhancements for observability applications using OpenSearch (e.g. ingestion, plugins, Alerting, Anomaly Detection, Dashboards).
* Align OpenSearch observability initiatives with industry trends, CNCF observability guidelines, and interoperability standards.
* Collaborate with external observability projects like OpenTelemetry, Prometheus, Jaeger, and Fluent Bit to enable seamless data ingestion, integration and interoperability. 
* Define and promote observability best practices for OpenSearch deployments, covering data ingestion pipelines, alerting, visualization, and operational monitoring.
* Coordinate with other OpenSearch SIGs and CNCF Operational Resilience TAG to align roadmaps, share insights, and contribute to cross-community initiatives.
* Initiate a review of the issues that are related to observability
    * Observability using OpenSearch including ingestion, storage for metrics, logs, traces, profiles, plugins such as alerting, anomaly detection, visualization and dashboards
    * Establish and maintain best practices of observing OpenSearch, including instrumenting OpenSearch, plugins, data prepper with metrics (e.g., Prometheus exporters, OTLP), logs, and traces for internal health monitoring and debugging.
* Review by a subject matter expert (SME) on the proposal
* Submit the findings and recommendations to the TSC via email

### Non-Goals

* The SIG will not govern or develop the core OpenSearch platform (e.g., indexing, search, replication mechanisms) except where directly related to observability data ingestion and storage.
* The SIG will not dictate observability practices outside the OpenSearch ecosystem but will engage with external communities (e.g., CNCF Observability TAG) for alignment and knowledge sharing.

### Participation

All participants must adhere to the OpenSearch Software Foundation’s Code of Conduct and the SIG’s operational guidelines to foster a respectful and inclusive environment.

#### Eligibility

* Subject Matter Expert, SME, in at least of the following categories relevant to the project
    * OpenSearch Core Engine: Key structures and fundamental components of OpenSearch Core
    * Dashboard Integrations: Enhancements and extensions for OpenSearch Dashboards
    * Plugins: Alerting, anomaly detection etc. that is relevant to observability
    * Ingestion Pipelines: Ingest processors for logs, metrics and traces, including integration with [data prepper](https://docs.opensearch.org/docs/latest/data-prepper/)
    * External Observability Projects such as Prometheus, OpenTelemetry, Jaeger, Fluent Bit

### Communications

* OpenSearch Slack [#observability](https://opensearch.slack.com/archives/C052APZA1FA)
* Meeting: Exact times and link TBD. Proposing once a month. The frequency to be adjusted on need basis. 
* Mailing List: TBD
* Project: New project to be opened in OpenSearch [projects](https://github.com/orgs/opensearch-project/projects?query=is%3Aopen) to keep track of the proposals, issues, requests
* Observability SIG members will communicate through email to review proposals and discuss feedback
* All feedback will be documented and shared with the community on the original issues / requests raised by the requester
* The feedback will also be sent to the TSC members through email so TSC members can make a final decision and vote
