# Maintenance Checklist

Recurring maintenance checks for repositories tracked in this repo.

## Weekly checks

- [ ] Review and triage new secret scanning alerts
- [ ] Review and triage new Dependabot alerts
- [ ] Confirm CI workflows are green on the default branch
- [ ] Sweep open issues and PRs for items with no activity in 14+ days

## Monthly checks

- [ ] Merge or act on outstanding Dependabot dependency updates
- [ ] Rotate or verify credentials and secrets referenced in workflows
- [ ] Confirm branch protection and required reviews are still enforced
- [ ] Review collaborators and team access for changes
- [ ] Clean up stale branches and old workflow run artifacts

## Release checks

- [ ] Tag the release following the documented tagging policy
- [ ] Confirm the tagged commit is the merged HEAD of the default branch
- [ ] Attach changelog / release notes to the release
- [ ] Verify security scans passed against the tagged commit
- [ ] Post-release: confirm the tag is reachable from the default branch
