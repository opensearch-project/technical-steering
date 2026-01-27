# OpenSearch Search Technical Advisory Group (TAG) Governance Charter

### Purpose

The OpenSearch Search Technical Advisory Group (TAG) provides strategic direction and technical guidance across all aspects of search - including core text search, vector search, semantic search, hybrid retrieval, relevance tuning, and performance. As OpenSearch expands into analytics, AI, and observability, search remains its foundation.

This TAG ensures OpenSearch remains competitive in the evolving search landscape by:
- Ensuring OpenSearch delivers compelling value in a rapidly evolving ecosystem with diverse search solutions and emerging AI-powered alternatives
- Integrating ML deeply into search (ML and Search are inseparable - query understanding, ranking, boosting, and signals are all ML problems)
- Bringing together diverse perspectives: core maintainers, plugin owners, product managers, data scientists, AI engineers, and community contributors
- Providing a unified strategy for advancing OpenSearch's search experience and aligning community efforts across repositories

### Responsibilities

The following is a non-exhaustive sample list of activities and deliverables that are in-scope for this TAG:

1. **Strategic Direction**: Guide OpenSearch search roadmap to address current and future industry trends. Ensure OpenSearch evolves with the search industry and anticipates where it's heading, delivering compelling value for diverse search use cases.

2. **Technical Guidance**: Review and advise on proposals impacting search behavior, query engine, or ranking logic. Provide expert input on design decisions affecting search functionality.

3. **Roadmap Alignment**: Help prioritize and unify search-related efforts across teams. Coordinate development of text search, vector search, semantic search, and hybrid retrieval features.

4. **Evaluation and Quality**: Enable users to navigate precision/recall and relevance/ranking trade-offs. Define hooks to measure overall effectiveness of search solutions. Address how to ensure hybrid inference setups don't silently degrade search performance.

5. **Core Primitives and Scale**: Address challenges at billion-vector scale including graph updates, vector space merging, filtered search, and cold start scenarios. Balance core engine innovations with ecosystem integrations.

6. **Lucene Lifecycle Governance and Upstream Alignment**: Formalize how OpenSearch requirements feed back into Lucene to maintain alignment with upstream. Manage divergence risks and ensure smooth Lucene version upgrades.

7. **Best Practices and User Experience**: Publish reference patterns for scaling, benchmarking, and tuning search and relevance. Improve developer experience and onboarding. Make OpenSearch more AI and ML ready.

8. **Agentic Search Platform**: Guide development of production-scale agentic search capabilities. Address rapidly updating enterprise context, query understanding, document representation, and intent alignment using Search+ML.

9. **ML Integration and Model Impact**: Provide guidance on how different ML outputs (single-vector, multi-vector, late interaction models) impact retrieval quality. Help users choose effective approaches for their use cases. Guide evolution of search internals to support cross-paradigm shifts.

10. **Cross-Domain Collaboration**: Coordinate with other TAGs where search intersects with their domains.

11. **Advisory Reports**: Submit recommendations to the TSC with clear technical rationale. Provide consolidated roadmap updates for text, vector, and hybrid search space.

### Non-Goals

* Search TAG will not govern or develop features outside the search domain (e.g., cluster management, data ingestion pipelines) except where directly related to search performance and functionality.
* Search TAG will not dictate implementation details for individual features but will provide strategic guidance and architectural direction.
* Search TAG will not replace existing maintainer responsibilities but will complement them with cross-cutting expertise and coordination.

### Participation

All participants must adhere to the OpenSearch Software Foundation's Code of Conduct and the TAG's operational guidelines to foster a respectful and inclusive environment.

#### Eligibility

* Subject Matter Expert (SME) in at least one of the following categories relevant to the project:
    * Lucene / OpenSearch core internals
    * Text analysis and ranking algorithms
    * Vector / semantic and hybrid retrieval systems
    * Large-scale search performance and benchmarking
    * Query engine architecture and optimization
    * Relevance tuning and scoring mechanisms
    * Search plugin development and extensibility
    * Search Product Management and user experience
    * Data Science and ML model integration with search
    * AI engineering and agentic search applications
    * Search industry trends and competitive analysis

### Communications

* OpenSearch Slack: [#search](https://opensearch.slack.com/archives/C0539F41Z5X)
* Meeting: [OpenSearch Meetup](https://www.meetup.com/opensearch/events/312788273/). Proposing once a month. The frequency to be adjusted on need basis. New Meetup will be shared soon.
* Mailing List: TBD
* Project: [Search Project Board](https://github.com/orgs/opensearch-project/projects/45/) to keep track of the proposals, issues, requests
* Search TAG members will communicate through email to review proposals and discuss feedback
* All feedback will be documented and shared with the community on the original issues / requests raised by the requester
* The feedback will also be sent to the TSC members through [github issues](https://github.com/opensearch-project/technical-steering/issues), slack or email so TSC members can make a final decision and vote if needed
