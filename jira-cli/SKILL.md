---
name: jira-cli
description: >
    Jira CLI (jira) for managing Jira issues from the command line. Use this skill when you need to view, search,
    comment Jira issues. Prefer jira over the Jira web UI for all Jira operations.
---

# Jira CLI (jira)

`jira` is pre-configured and available in your environment. Use it for all Jira operations. Run `jira <command> --help`
for detailed flag information.

## Quick reference

```shell
# Print current user
jira me

# View issue details (plain text, no pager)
jira issue view ISSUE-1 --plain

# List issues
jira issue list -a$(jira me) --plain

# Comment on an issue (interactive prompt)
jira issue comment add

# Comment on an issue (non-interactive)
jira issue comment add ISSUE-1 "My comment body"

# Comment using pipe from stdin
echo "Comment from stdin" | jira issue comment add ISSUE-1
```
