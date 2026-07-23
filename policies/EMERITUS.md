- [Overview](#overview)
- [Self-Initiated: Moving On](#self-initiated-moving-on)
- [External: Inactivity](#external-inactivity)
  - [Identifying Inactivity](#identifying-inactivity)
  - [Outreach](#outreach)
  - [Moving to Emeritus](#moving-to-emeritus)
- [Reinstatement](#reinstatement)
- [Relationship to At-Risk Status](#relationship-to-at-risk-status)

## Overview

Emeritus is an honorary status for maintainers who are no longer actively involved with a repository. It is not punitive, recognizes prior contributions, and an Emeritus maintainer can be reinstated at any time at their own request.

The [RESPONSIBILITIES.md](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md) document defines two paths for moving a maintainer in good standing to Emeritus:

  1. ([Moving On](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#moving-on)) — the maintainer voluntarily opens a pull request moving themselves to the Emeritus section of `MAINTAINERS.md`.
  2. ([Inactivity](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#inactivity)) — the admin team opens a pull request moving an inactive maintainer to the Emeritus section on their behalf.

> **A note on the tension between the two paths:** Emeritus is framed primarily as something a maintainer chooses for themselves. The Inactivity path exists because the maintainers most in need of being moved to Emeritus — those who have gone silent — are, by definition, the least likely to file the PR themselves. When the project must act on a maintainer's behalf, that action should be done respectfully, with prior outreach, and with the understanding that the maintainer may return at any time.

This document does not cover removal for [Negative Impact on the Project](https://github.com/opensearch-project/.github/blob/main/RESPONSIBILITIES.md#negative-impact-on-the-project), which is a separate process handled by the admin team.

## Moving On

A maintainer who wishes to step back follows these steps:

1. Open a pull request against the repository's `MAINTAINERS.md` moving themselves from the active maintainers section to the Emeritus section, and updating `CODEOWNERS` to remove their entries.
2. Notify the [members of the admin team](https://github.com/opensearch-project/.github/blob/main/ADMINS.md), typically by opening an issue in the [opensearch-project/.github](https://github.com/opensearch-project/.github) repo, to request that their maintain-level permissions be revoked.
3. The admin team merges the PR and revokes the permissions.

## Inactivity

Part of having a strong security posture for the Project is adhering to the principle of least privilege: maintainers credentials should be scoped to people that actively need them. Therefore, when a maintainer has been inactive for a period of a year without moving themselves to Emeritus, the project may move them to Emeritus on their behalf.

### Identifying Inactivity

Inactivity is defined as not using maintainer privileges for a period of 1 year or more in a specific repo.  The 1 year time frame is a default choice, there may be specific repos where this time frame is too short or too long.

Inactivity can be identified via the [OpenSearch Maintainer Dashboard](https://metrics.opensearch.org/_dashboards/app/dashboards?security_tenant=global#/view/30fedc30-9ae2-11ef-a168-f19b1bbc360c?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:now-30d,to:now))&_a=(description:'Shows%20data%20about%20the%20activity%20of%20maintainers%20in%20the%20OpenSearch%20Project(since%2010-12-24,%20and%20the%20technical-steering%20repo%20since%2011-7-24).%20',filters:!(),fullScreenMode:!f,options:(hidePanelTitles:!f,useMargins:!t),query:(language:kuery,query:''),timeRestore:!t,title:'OpenSearch%20Maintainer%20Dashboard',viewMode:view)).

The dashboard labels a maintainer with status 'Inactive' if they have no activity in the repository using the default timeframe of the past year.

### Outreach

An existing maintainer or a member of the admin team opens a PR moving the inactive maintainer to emeritus in MAINTAINERS.md and removing from CODEOWNERS with the comment:

```
Hey @inactive-maintainer, we see you haven't used your maintainer privileges in the [past year](https://metrics.opensearch.org/_dashboards/app/dashboards?security_tenant=global#/view/30fedc30-9ae2-11ef-a168-f19b1bbc360c?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:now-30d,to:now))&_a=(description:'Shows%20data%20about%20the%20activity%20of%20maintainers%20in%20the%20OpenSearch%20Project(since%2010-12-24,%20and%20the%20technical-steering%20repo%20since%2011-7-24).%20',filters:!(),fullScreenMode:!f,options:(hidePanelTitles:!f,useMargins:!t),query:(language:kuery,query:''),timeRestore:!t,title:'OpenSearch%20Maintainer%20Dashboard',viewMode:view)) for this repo. 
If you plan on continuing to contribute, please respond here and close this PR. Otherwise, per our [inactivity policy](https://github.com/opensearch-project/technical-steering/blob/main/policies/RESPONSIBILITIES.md#inactivity) you'll be moved to emeritus, but you can move back to active status at any time.
```

Here [is an example PR]([https://github.com/opensearch-project/OpenSearch/pull/21144).

If, after seven days, there is no reply to the PR, then an existing maintainer or member of the admin team merges the PR.

## Reinstatement

Emeritus status is not permanent. Any past maintainer can be reinstated at any time:

- The returning maintainer or another current maintainer opens a pull request moving them from the Emeritus section back to the active maintainers section, and restoring `CODEOWNERS` entries.
- The [members of the admin team](https://github.com/opensearch-project/.github/blob/main/ADMINS.md) restore the maintainer's permissions upon merge.

## Relationship to At-Risk Status

Moving inactive maintainers to Emeritus is one of the ways a repository can transition into [At-Risk status](AT_RISK_REPO.md): once active maintainers fall below three, the At-Risk process begins. In practice these processes often run in parallel — the same outreach that confirms a maintainer should be moved to Emeritus may also surface the need to identify new maintainers under the At-Risk process.

The one year time frame for identifying inactivity is a choice.  Some simple stable repos may not require much maintainer involvement, and for them, the time frame may be much longer before triggering the Emeritus process.  This should be evaluated on a repo by repo basis.
