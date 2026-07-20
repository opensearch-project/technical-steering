- [Overview](#overview)
- [Identifying At-Risk Repositories](#identifying-at-risk-repositories)
- [How We Add New Maintainers](#how-we-add-new-maintainers)

## Overview

This document explains how we identify repositories that do not have sufficient maintainers to provide their own governance and then add new maintainers.

## Identifying At-Risk Repositories

Active maintainers provide the governance structure for each repository.  Identifying if a repo is At Risk is determined via the [OpenSearch Maintainer Dashboard](https://metrics.opensearch.org/_dashboards/app/dashboards?security_tenant=global#/view/30fedc30-9ae2-11ef-a168-f19b1bbc360c?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:now-30d,to:now))&_a=(description:'Shows%20data%20about%20the%20activity%20of%20maintainers%20in%20the%20OpenSearch%20Project(since%2010-12-24,%20and%20the%20technical-steering%20repo%20since%2011-7-24).%20',filters:!(),fullScreenMode:!f,options:(hidePanelTitles:!f,useMargins:!t),query:(language:kuery,query:''),timeRestore:!t,title:'OpenSearch%20Maintainer%20Dashboard',viewMode:view)).

The dashboard labels a maintainer with status 'Inactive' if they have no activity in the repository in the past year.

If less than three maintainers are active, then the repository is considered At Risk.

## How We Add New Maintainers

At times the maintainers of a repository may have become inactive or moved to Emeritus status, leaving behind an repository that no longer has a quorum for voting in new maintainers. Adding new maintainers in this situation requires an exception process run by the Technical Steering Committee (TSC), because the standard [nomination process](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#nomination) assumes a quorum of at least three active maintainers are available to nominate and vote.

Once a repository is considered At Risk, the following steps are taken:

1. An issue is opened in the [technical-steering](https://github.com/opensearch-project/technical-steering) repo to track the process, similar to [[PROPOSAL] Unmaintained OpenSearch k8s operator repo #60](https://github.com/opensearch-project/technical-steering/issues/60).
2. A TSC member starts an email thread with existing maintainers notifying them of the At-Risk status and invites the existing maintainers to either resume activity, propose candidates themselves, or accept community-proposed candidates.
  * **If we did this as a GitHUB issue, we could then do soemthing similar to https://www.apache.org/dev/pmc.html#roll-call witht he three questions.  If maintainers respond +1 I am active, wouldn't that reset the OpenSearch Maintainer Dashboard clock on acitve/inactive?   Maybe we need to do BOTH however.**   
  * **If enough non active maintainers say they are active via the comments on github issue, then the issue could be closed.**
 * **Or just check back a month later and see if activity has happened?  Having a "Is this repo alive issue" might be bad optics.**
3. Any community member or TSC member may propose candidates who have demonstrated sustained interest in the repository through pull requests, issue triage, blog posts, or related contributions.
4. A TSC member starts a seperate email thread with existing maintainers notifying them of potential community-proposed candidates for maintainership. The existing maintainers must either start the standard [nomination process](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#nomination), or respond with reasons why the proposed maintainers are not suitable and a plan for on-going governance of the repo.   If the TSC accepts the plan then the issue is closed.
5. If, after seven days, there is no reply to the email thread, then a follow-up email is sent.
6. If, after a further seven days (14 days total), there is still no reply from existing maintainers, then the exception process is followed:
   - The community/TSC member who proposed the candidate in step 3 shares with the TSC the name and background of the potential candidate.
   - A single member of the TSC has a discussion with the candidate about the responsibilities of being a maintainer. A full TSC vote is not required; that one member's positive feedback is sufficient to proceed.
   - Assuming positive feedback, a ticket is opened with the OpenSearch Project admins similar to [[GitHub Request] Add github.com/synhershko as a maintainer of opensearch-k8s-operator](https://github.com/opensearch-project/.github/issues/405).
   - A member of the TSC opens the PR in the repo for updating `CODEOWNERS` and `MAINTAINERS.md` similar to [Add SamuelCox nomination](https://github.com/opensearch-project/opensearch-net/pull/960).
7. Once the new maintainer(s) have been added, the original issue in the `technical-steering` repo is closed.

Note: The repository may still be At Risk until there are three active maintainers, which means this process may need to be run multiple times.
