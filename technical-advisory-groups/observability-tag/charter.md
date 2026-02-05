# OpenSearch Observability Technical Advisory Group (TAG) Governance Charter

### Purpose

The OpenSearch Observability Technical Advisory Group (TAG) champions the strategic direction and technical guidance for observability solutions within the OpenSearch ecosystem. Our core purpose is to define, advocate for, and spread best practices and architectures that empower users to effectively implement and leverage OpenSearch for their logs, traces, and metrics, ultimately providing informed recommendations to the Technical Steering Committee (TSC).

### Responsibilities

The following is a non-exhaustive sample list of activities and deliverables that are in-scope for this TAG

1. Provide technical guidance and strategic direction for observability applications using OpenSearch. Conduct review of issues related to observability using OpenSearch including, but not limited to storage for metrics, logs, traces, profiles; ingestion, visualization, dashboards and plugins such as alerting, anomaly detection, integrations in [OpenSearch Observability Catalog](https://github.com/opensearch-project/opensearch-catalog/tree/main).

2. Align OpenSearch observability initiatives with industry trends, CNCF observability guidelines, and interoperability standards by collaborating with external observability projects (OpenTelemetry, Prometheus, Jaeger, Fluent Bit etc.) to ensure seamless data ingestion, integration, and interoperability. Coordinate with other OpenSearch SIGs and CNCF Operational Resilience TAG.

3. Establish and advocate for observability best practices for OpenSearch deployments, encompassing data ingestion pipelines, alerting, visualization, and operational monitoring while fostering community growth and expand user adoption.


### Non-Goals

* Observability TAG will not govern or develop the core OpenSearch platform (e.g., indexing, search, replication mechanisms) except where directly related to observability data ingestion and storage.
* Observability TAG will not govern features or plugin that are used for other purposes.
* Observability TAG will not dictate observability practices outside the OpenSearch ecosystem but will engage with external communities (e.g., CNCF Observability TAG) for alignment and knowledge sharing.

### Participation

All participants must adhere to the OpenSearch Software Foundation’s [Code of Conduct](https://github.com/opensearch-project/.github/blob/main/CODE_OF_CONDUCT.md) and the SIG’s operational guidelines to foster a respectful and inclusive environment.

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
