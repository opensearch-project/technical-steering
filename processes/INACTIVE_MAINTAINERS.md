
## Process

1. Find inactive maintainer using [metrics dashboard](https://metrics.opensearch.org/_dashboards/app/dashboards#/view/30fedc30-9ae2-11ef-a168-f19b1bbc360c)
1. Filter out archived repos
1. Open a PR using the template text below
1. Wait seven days
1. Close or merge the PR per the instructions in the template text



## PR Template Text

```
Hey @{GITHUB_HANDLE}, we noticed you haven't used your maintainer privileges
in this repository over the past year. Per the OpenSearch Project
[inactivity policy](https://github.com/opensearch-project/technical-steering/blob/main/policies/RESPONSIBILITIES.md#inactivity),
maintainers inactive for 12 months or more are moved to emeritus status.

**If you plan to continue contributing as a maintainer**, please respond here
and close this PR and no further action is needed.

Otherwise, this PR will move you to the emeritus list. Emeritus status is
not permanent: you can return to active maintainer status at any time by
expressing interest to the current maintainers.

**Existing maintainers**: Please merge this PR once @{GITHUB_HANDLE} confirms
they do not plan to use their maintainer privileges, or after 7 days with no
response. If neither maintainers nor @{GITHUB_HANDLE} take any action within
7 days, a member of the [admin team](https://github.com/orgs/opensearch-project/teams/admin)
will merge it.

### Activity data

This determination is based on the
[OpenSearch Maintainer Dashboard](https://metrics.opensearch.org/_dashboards/app/dashboards#/view/30fedc30-9ae2-11ef-a168-f19b1bbc360c)
(filter by repository: `{REPO_NAME}`). If you believe the activity data is
mistaken, please say so here so we can investigate before merging.
```
