# AcUtils

## pull-request

Usage `pull-request <tracking-branch>`

Pushes your changes and opens a PR directly in github. A default tracking-branch can be defined by putting `export CURRENT_BRANCH="version-8.3"` in your .bash_profile

## jira-id

Usage `jira-id`

Looks in the git log for the last used JIRA ID. It will then echo it and copy it to the clipboard. Add `command J r!jira-id` to your .vimrc to insert the last used JIRA ID into your commit message by running `:J`

## branch

Usage `branch <upstream-branch> <local-branch>`

Fetches all existing changes from git, and then creates a local branch from the upstream provided