# OpenSearch Observability Technical Advisory Group (TAG) Governance Charter

### Purpose

The OpenSearch Project proposes to create a Observability Interest Group that focuses on observability using OpenSearch. This includes logs, traces, metrics, and future signals using OpenSearch. This group will also establish guidelines for members, set architecture guidelines, and come up with recommendations which will then be reviewed by TSC for decision making. The group will provide feedback to the TSC before the final decision is made through voting of TSC members.

### Responsibilities

The following is a non-exhaustive sample list of activities and deliverables that are in-scope for this TAG

1. Provide technical guidance and strategic direction for observability applications using OpenSearch (e.g. ingestion, plugins, Alerting, Anomaly Detection, Dashboards).

    * Conduct review of issues related to observability solutions within the [OpenSearch Observability Catalog](https://github.com/opensearch-project/opensearch-catalog/tree/main), storage for metrics, logs, traces, profiles, as well as ingestion, and plugins such as alerting, anomaly detection, visualization and dashboards
    * Establish and maintain best practices of observing OpenSearch, including instrumenting OpenSearch, plugins, data prepper with metrics, logs, and traces (e.g., Prometheus exporters, OTLP, Jaeger)for internal health monitoring and debugging.
    * Get issues and proposal reviewed by a subject matter expert (SME)

2. Align OpenSearch observability initiatives with industry trends, CNCF observability guidelines, and interoperability standards by collaborating with external observability projects (OpenTelemetry, Prometheus, Jaeger, Fluent Bit etc.) to ensure seamless data ingestion, integration, and interoperability. Coordinate with other OpenSearch SIGs and CNCF Operational Resilience TAG.

3. Establish and advocate for observability best practices for OpenSearch deployments, encompassing data ingestion pipelines, alerting, visualization, and operational monitoring while fostering community growth and expand user adoption.


### Non-Goals

* Observability TAG will not govern or develop the core OpenSearch platform (e.g., indexing, search, replication mechanisms) except where directly related to observability data ingestion and storage.
* Observability TAG will not govern features or plugin that are used for other purposes.
* Observability TAG will not dictate observability practices outside the OpenSearch ecosystem but will engage with external communities (e.g., CNCF Observability TAG) for alignment and knowledge sharing.

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
* Observability TAG members will communicate through email to review proposals and discuss feedback
* All feedback will be documented and shared with the community on the original issues / requests raised by the requester
* The feedback will also be sent to the TSC members through [github issues](https://github.com/opensearch-project/technical-steering/issues), slack or email so TSC members can make a final decision and vote if needed
