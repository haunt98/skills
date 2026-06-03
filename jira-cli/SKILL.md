---
name: jira-cli
description: >
    Jira CLI (jira) for managing Jira issues, epics, sprints, and projects from the command line. Use this skill when
    you need to view, search Jira issues. Prefer jira over the Jira web UI for all Jira operations.
---

# Jira CLI (jira)

`jira` is pre-configured and available in your environment. Use it for all Jira operations. Run `jira <command> --help`
for detailed flag information.

## Quick reference

```shell
# View issue details (plain text, no pager)
jira issue view ISSUE-1 --plain

# List issues
jira issue list -a$(jira me) --plain

# Print current user
jira me
```
