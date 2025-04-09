# OpenSearch Special Interest Groups ("SIGs")

## Introduction

This document defines the basic structure and life cycle of Special Interest Groups (SIGs) within the OpenSearch Project. More information about specific SIGs can be found within their respective charter documents.

## Purpose

An OpenSearch SIG will oversee and coordinate the interests pertaining to a logical area of needs of end users and/or projects. Examples of such areas include security, testing, storage, repository health and management, etc. SIGs are:
- Long-lived groups that report to the Technical Steering Committee (TSC)
- Led by recognized experts in the relevant fields, supported by other contributors

## Operating Model

### Formation

The Technical Steering Committee takes responsibility for establishment of SIGs. A new SIG can be proposed to the TSC by presenting a charter document. Upon a successful vote of the TSC, the charter will be committed to https://github.com/opensearch-project/technical-steering/tree/main/special-interest-groups.

### Membership

#### Adding a Member

SIGs are responsible for maintaining their own membership, similar to how maintainers are managed within code repositories. To nominate a new member, any current SIG member starts a private e-mail thread with all other members to discuss nomination. In order to be approved, at least three positive (+1) votes are necessary, and no vetoes (-1). Upon receiving the necessary votes from existing members after a one week period, the nominating member asks the nominee whether they would like to join the SIG via private e-mail message. If the nominee accepts, they are then added via a pull request to the SIG charter document.

#### Removing a Member

Reasons to remove a member:

- Moving On: 
  - There are plenty of reasons that might cause someone to want to take a step back or even a hiatus from a project. Existing members can choose to leave the project at any time, with or without reason, by making a PR to move themselves to the "Emeritus" section of this file.
- Inactivity: 
  - Member status never expires. If a member becomes inactive for a time (usually 6 months), or a member can confirm that they are no longer involved with the project for any reason, the members of the admin team may make a pull request to move them to the "Emeritus" section of this file.
- Negative Impact: 
  - Actions that negatively impact the project will be handled by the members of the admin team, in coordination with other members, in balance with the urgency of the issue. Examples would be Code of Conduct violations, deliberate harmful or malicious actions, and security risks.

Initial membership of newly formed SIGs should be included in the proposal document that is voted on by the TSC.

### Amendments

A SIG’s responsibilities may be amended via a pull request to the charter document in the technical-steering repository. All amendments must be approved by the TSC.

### Retirement

In the event a SIG is no longer able to fulfill its responsibilities, the TSC may, by means of a 2/3 majority vote, declare “no confidence” in the SIG. In this event, the TSC may vote to retire or reconstitute the SIG.
