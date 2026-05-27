- [Overview](#overview)
## Overview

This document explains how we manage repositories that do not have sufficient maintainers to provide their own governance.

## Identifying Orphaned Repositories
blah blah blah.

## How we add new Maintainers

At times the maintainers of a repository may have moved on and no longer be active, leaving behind an orphaned repository. Adding new maintainers in this situation requires an exception process run by the Technical Steering Committee (TSC), because the standard [nomination process](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#nomination) assumes active maintainers are available to nominate and vote.

Once a repository is considered orphaned, the following steps are taken:

1. An issue is opened in the [technical-steering](https://github.com/opensearch-project/technical-steering) repo to track the process, similar to [[PROPOSAL] Unmaintained OpenSearch k8s operator repo #60](https://github.com/opensearch-project/technical-steering/issues/60).
2. New potential maintainers are identified to join the repository. Any community member or TSC member may propose candidates who have demonstrated sustained interest in the repository through pull requests, issue triage, blog posts, or related contributions.
3. A TSC member starts an email thread with existing maintainers notifying them of potential new maintainers. The existing maintainers must either start the standard [nomination process](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#nomination), or respond with reasons why the proposed maintainers are not suitable and a plan for on-going maintenance of the repo.
4. If, after seven days, there is no reply to the email thread, then a follow-up email is sent.
5. If, after seven days, there is still no reply from existing maintainers, then the exception process is followed:
   - The community/TSC member who proposed the candidate in step 2 shares with the TSC the name and background of the potential candidate.
   - A member of the TSC has a discussion with the candidate about the responsibilities of being a maintainer.
   - Assuming positive feedback, a ticket is opened with the OpenSearch Project admins similar to [[GitHub Request] Add github.com/synhershko as a maintainer of opensearch-k8s-operator](https://github.com/opensearch-project/.github/issues/405).
   - A member of the TSC opens the PR in the repo for updating `CODEOWNERS.md` and `MAINTAINERS.md` similar to [Add SamuelCox nomination](https://github.com/opensearch-project/opensearch-net/pull/960).
6. Once the new maintainer(s) have been added, the original issue in the `technical-steering` repo is closed.


* Do we try to define orphan repo in this?  And of course, let's bike shed the file name!
* What happens when you have 1 active maintainer? HOw do we get to 2 and then 3?  Once we have 3 active, we are good to go right?  
* Are we good with the 1 tsc member as the "quorum" in the exception path?  Do we need multiple TSC members?  (seems like a lot)
