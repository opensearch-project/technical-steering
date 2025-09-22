# OpenSearch Technical Steering Committee Election Process

## Overview

This document establishes the election procedures for the OpenSearch Technical Steering Committee (TSC) as referenced in Section 3.e of the [OpenSearch Project Technical Charter](https://opensearch.org/wp-content/uploads/2025/02/OpenSearch-Project-Technical-Charter-Final-9-13-2024.docx.pdf). The TSC will hold elections annually to fill expiring terms and maintain continuity of technical oversight for the OpenSearch Project. The committee size includes 15 members; an odd number required for any voting.

## Election Timeline

### Annual Election Schedule

- **End of term**: Facilitator opens form for community nominations for 2 weeks
- **Nomination period**: Call for nominations opens; exception request period opens
- **Prior to next TSC Meeting**: Nominations and exception requests close; candidate statements collected by facilitator
- **During TSC Meeting**: Voting by current TSC members will take place at next scheduled TSC meeting
- **Within 3 Days of Vote**: Results announced and certified
- **Implementation**: New TSC members take office at the next scheduled TSC meeting
- **Chair Election**: During the first meeting with new TSC members, a chair will be nominated and voted upon. 

Elections will be held annually, with the timing determined by the TSC to ensure adequate transition time before expiring terms end.

## Facilitator

### Responsibilities
Election Facilitator is responsible for:
- Publishing all election announcements and communications
- Maintaining and publishing the eligible voter list
- Processing voter eligibility exception requests
- Preparing and distributing electronic ballots
- Assisting candidates with statement preparation and publication
- Monitoring the voting process for integrity
- Tallying results according to the procedures in this document
- Announcing results and certifying the election

## Voter Eligibility

### Primary Eligibility Criteria
The first voting of new member elections will be held by the TSC. This is to get through the process successfully for its first voting iteration, and to ensure goals of electing new members is completed in a timely manner.

## Candidate Eligibility

### Basic Requirements
To be eligible as a candidate, individuals must:
- Be an active Project Maintainer or Contributor as defined in the [OpenSearch Project Technical Charter](https://opensearch.org/wp-content/uploads/2025/02/OpenSearch-Project-Technical-Charter-Final-9-13-2024.docx.pdf) (section 2e)
- Have demonstrated significant technical leadership within the OpenSearch Project
- Commit to serving the full term if elected

### Nomination Process
Candidates may:
- Self-nominate by submitting a nomination form during the nomination period
- Be nominated by any other eligible voter (with candidate's consent)
- Be a current TSC member running for re-election

### Candidate Materials
Each new candidate must provide:
- A candidate statement (maximum 500 words) describing:
  - Their technical contributions to the OpenSearch Project as defined in the [OpenSearch Project Technical Charter](https://opensearch.org/wp-content/uploads/2025/02/OpenSearch-Project-Technical-Charter-Final-9-13-2024.docx.pdf) (section 2e)
  - Their vision for the project's technical direction
  - Specific areas they would focus on as a TSC member
  - Their commitment to serving the full term
- A brief biography highlighting relevant experience
- Links to significant technical contributions, MAINTAINER docs they are part of, or technical proposals

Each candidate seeking re-election must provide:
- A note on the candidate nomination issue stating 're-election'
- Their commitment to serving the full term

*Candidate entries that do not contain all relevant information will be excluded from vote*

## Voting Procedure

### Voting Method
Elections will use a **Condorcet ranking method with Instant Runoff Voting (IRV)** for tiebreaking. This method ensures that:
- Voters rank candidates in order of preference
- The candidate with the strongest overall support wins
- Strategic voting is minimized

*Voting mechanisms will be handled within the LFX Project Control Center tooling by the facilitator*

### Ballot Distribution
Election Facilitator will distribute secure electronic ballots to all eligible voters using a system that ensures:
- Ballot secrecy and voter privacy
- Prevention of duplicate voting
- Auditability of results
- Accessibility for all eligible voters

### Voting Period
- Minimum voting period: During a scheduled TSC meeting
- Voting period will be clearly communicated and may be extended only for technical issues

### Vote Counting
The Election Facilitator will:
- Use the Condorcet method to determine electees
- Apply IRV for tiebreaking when necessary
- Fill available seats with the candidates receiving the highest rankings
- Apply company representation limits (see below)
- Publish aggregated results while maintaining individual ballot secrecy
- Update [/technical-steering/MEMBERS.md](https://github.com/opensearch-project/technical-steering/blob/main/MEMBERS.md) file - non-active members moved to Former Members
- Update [/technical-steering/MAINTAINERS.md](https://github.com/opensearch-project/technical-steering/blob/main/MAINTAINERS.md) file - non-active members moved to Emeritus

## Special Elections and Vacancies

### Vacancy Filling
When a TSC member resigns or is otherwise unable to serve:
1. The candidate with the next highest vote count from the most recent election will be offered the seat
2. If that candidate is unavailable or ineligible, the offer proceeds to subsequent candidates
3. If no suitable candidates remain from the previous election, a special election will be held

### Special Election Triggers
A special election will be called when:
- Normal vacancy filling process fails to fill a seat
- More than one vacancy exists simultaneously
- The regular election is more than 7 weeks away

### Special Election Process
Special elections will follow the same procedures as regular elections but with a compressed timeline:
- Use the same voter eligibility list as the most recent election
- 1-week nomination period
- Winners serve the remainder of the original term

## Election Integrity and Appeals

### Monitoring
Election Facilitator will monitor the election for:
- Technical issues with voting systems
- Attempts at voter fraud or manipulation
- Violations of election procedures
- Complaints about candidate conduct

### Appeals Process
Any eligible voter may appeal election results or procedures by:
- Submitting a written appeal to facilitator within 3 days of result announcement
- Providing specific details about alleged irregularities
- Requesting specific remedies

Facilitator will investigate appeals and may:
- Correct minor procedural issues
- Extend voting periods for technical problems
- In extreme cases, recommend a new election to the TSC

### Final Authority
The TSC retains final authority over election disputes that cannot be resolved by facilitator.

## Election Documentation and Transparency

### Public Records
The following will be maintained as public records:
- This election procedures document
- Election timeline and announcements
- Candidate statements and materials
- Final results
- Appeals and their resolutions

### Privacy Protection
The following will be kept confidential:
- Individual ballot choices
- Specific voter identities (unless publicly disclosed)
- Exception request details for unsuccessful applicants

## Amendments to Election Procedures

This Election Procedures Document may be amended by:
- Majority vote of the current TSC
- Following the amendment procedures specified in the OpenSearch Technical Charter
- With appropriate notice to the community for feedback

## Chair Election

In the event the current TSC chair steps down or does not seek re-election for the next term, a new chairperson will be required. 

- **First Meeting**: During the first session of the newly elected TSC
- Facilitator will begin meeting with nomination process
    - Chairperson must commit to serving the full term
- Voting Procedure mentioned in this document will commence
- New TSC members will have remainder of meeting to vote
- Facilitator will announce new TSC Chairperson

## Limitations on Company Representation

No more than 5 seats may be held by employees of the same organization (or
conglomerate, in the case of companies owning each other). If an
election results in greater than 5 employees of the same organization being
selected, the lowest vote getters from any particular employer will be removed until representation on the committee is down to 5.

If employers change because of job changes, acquisitions, or other events, in a
way that would yield too many seats being held by employees of the same
organization, sufficient members of the committee must resign until only 5
employees of the same employer are left. If it is impossible to find sufficient
members to resign, all employees of that organization will be removed and new
special elections held. In the event of a question of company membership (for
example evaluating independence of corporate subsidiaries) a majority of all
non-involved Steering Committee members will decide.

## References

- OpenSearch Project Technical Charter
- OpenSearch Project Governance Documents
- CNCF Project Template for Steering Committee Elections

---

*This document establishes the procedures for TSC elections as referenced in Section 3.e of the OpenSearch Project Technical Charter. It is maintained by the TSC and updated as needed to ensure fair, transparent, and effective elections.*
