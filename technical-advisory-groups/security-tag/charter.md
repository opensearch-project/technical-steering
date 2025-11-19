# OpenSearch Security Technical Advisory Group (TAG) Governance Charter

### Purpose

The OpenSearch Security Technical Advisory Group (TAG) champions the strategic direction and technical guidance for security across the OpenSearch ecosystem. Our core purpose is to define, advocate for, and spread best practices, architectures, and processes that empower users, contributors, maintainers and solution-builders of OpenSearch to design, implement and operate secure systems — ultimately providing informed recommendations to the OpenSearch Software Foundation (OSSF) Technical Steering Committee (TSC).

### Responsibilities

The following is a non-exhaustive sample list of activities and deliverables that are in-scope for this TAG:

1. Provide technical guidance and strategic direction on security features, practices and implementations across the OpenSearch stack — including, but not limited to: encryption (at rest, in transit), authentication and identity management, role-based access control (RBAC), audit logging, plugin security, cluster hardening and secure defaults.
2. Shape and maintain the security response process for OpenSearch (for example, improving the process documented in SECURITY.md).
3. Define, publish and advocate for security best practices across the ecosystem: e.g., dependency management (e.g., use of Mend, Dependabot) and secure development practices.
4. Review and provide feedback on security-related proposals, RFCs, issues, features or plugins — making explicit the security review process for enabling new features in OpenSearch.
5. Engage with external security standards, open-source security communities and industry frameworks (for example supply-chain security, cloud-native security, SCA, SBOM, threat modelling) to ensure OpenSearch remains aligned with emerging risks, best practices and interoperability.
6. Serve as a focal forum for community discussion of security topics, coordinating with relevant Special Interest Groups (SIGs), TAGs (e.g., Observability TAG) and the TSC to ensure security is integrated holistically.
7. Support awareness, education and adoption of secure OpenSearch deployments by the community—helping users understand how to operate OpenSearch securely in production.

### **Non-Goals**

* The Security TAG will **not** cover or govern **Security Analytics**, detections, rules engines, SIEM-style analytics features, or threat-hunting workflows. These fall under other SIGs/TAGs or future specialized working groups.


### Participation

All participants must adhere to the OSSF Code of Conduct and the TAG’s operational guidelines to foster a respectful, inclusive, and transparent environment.

#### Eligibility

To become a member of the Security TAG, a participant should be a subject-matter expert (SME) in one or more of the following areas relevant to the project:

* Security architectures for large-scale search and analytics systems (for example OpenSearch core engine, cluster/network security)
* Secure plugin and extension development for OpenSearch (for example authentication, authorization, audit logging)
* Dependency management, supply chain security, CI/CD security, vulnerability remediation (for example use of Mend/Dependabot)
* Compliance, operational security, incident/response practices in search/analytics ecosystems.

Members should commit to regular participation (meetings, reviews, discussions), and be willing to champion the activities of the TAG in the broader community.

### Communications

* Slack channel: #security (or equivalent in OpenSearch Slack workspace)
* Meeting cadence: Proposing monthly meetings as a starting point; frequency may be adjusted based on need
* Mailing list: TBD (to be established)
* Project board: A dedicated project under the OpenSearch GitHub org (in the Projects area) to track proposals, issues, requests, reviews and TAG deliverables
* Interaction protocol:

  * All review feedback, proposals, and recommendations will be documented on GitHub issues in the relevant repository or in a designated TAG-tracking repo.
  * Feedback from the Security TAG to the TSC will be communicated via GitHub issues (in the TSC repo), Slack or email, so the TSC can take final decision/vote if required.
  * All meetings and decisions are open to the community, and meeting notes/minutes will be published publicly.

### Decision & Escalation Process

* The role of the TAG is advisory; it **recommends** but does not enforce. Final decision-making (e.g., feature approvals, project road-map prioritization) rests with the TSC or respective project owners.
* When the TAG identifies a high-impact security concern (for example a critical vulnerability, supply-chain risk, plugin ecosystem-wide issue) it will escalate to the TSC and the security response team as appropriate.
* For proposals brought to the TAG: the proposer should raise a GitHub issue (or PR) and tag with “security-review” label. The TAG allocates a reviewer/team, issues feedback, and the outcome is documented in the issue or review comments.
* The TAG may create working groups/sub-teams to focus on specific security topics (e.g., supply-chain, incident response, plugin-hardening); these sub-teams will report status to the broader TAG and propose deliverables.

### Term & Membership Rotation

* Membership terms (for core members) will be defined (for example 12 months) with the option for renewal.
* The TAG may maintain a “core” or “steering” subset for operational continuity, while other participants may be “community members” with lighter commitments.
* New members may be nominated by existing TAG members or the TSC, and subject to consensus of current membership.
* Membership renewal, removal or rotation decisions will follow a transparent process documented in a TAG governance file.

### Metrics & Success Criteria

To measure the effectiveness of the Security TAG, the following indicators may be tracked:

* Number of security proposals for review by the TAG per quarter
* Number of published security-best-practice documents or guides (for developers, operators) for OpenSearch
* Level of community participation in TAG meetings and Slack/mailing list discussions

### Charter Review

This charter should be reviewed at least annually, or earlier if major changes in scope or project governance occur. Amendments to the charter will be proposed via a public GitHub issue, discussed by the TAG, and approved by the TSC.
