# Incident Response Playbook

This repository is the platform team's single source of truth for on-call incident
response. It replaces our scattered notes with a structured, reviewable set of
runbooks that any engineer — including teammates joining the rotation next
quarter — can pick up and execute under pressure.

## What lives here

| Path | Purpose |
| ---- | ------- |
| `docs/severity-levels.md` | Definitions of SEV-1 through SEV-4 and the response each level triggers |
| `docs/escalation-paths.md` | Who to page, in what order, when an incident needs more hands |
| `docs/oncall-rotation.md` | Current on-call rotation schedule and handoff notes *(draft, in review)* |

## Planned runbooks

Coverage work is tracked in GitHub issues under the epic
**Epic: Incident response runbook coverage**:

- Runbook: total service outage
- Runbook: failed deployment
- Runbook: data restoration

## How to contribute

1. Cut a branch from `main` (for docs work, `docs-*` branches are the convention).
2. Keep runbooks short, checklist-first, and command-oriented.
3. Open a pull request and request a review from someone who has carried the pager.

## On-call expectations

- Acknowledge pages within 5 minutes.
- Update the incident thread at least every 30 minutes during a SEV-1/SEV-2.
- Write a postmortem within two business days of any SEV-1.
