# Kickoff Status — Incident Response Playbook

**Account:** HeziLiu
**Date:** 2026-10-21

## 1. Repository

- **Name:** incident-response-playbook
- **Location:** https://github.com/mcpmark-eval-liuhezi/incident-response-playbook
- **Default branch:** `main`
- **Note:** The access token used cannot create repositories in the personal namespace (HTTP 403 — "Resource not accessible by personal access token"), so the work was set up in the organization `mcpmark-eval-liuhezi` (owned by this account). The repo was already initialized there with a README; all requested content has been added on top of it.
- **Content on `main`:**
  - `README.md` — rewritten with a proper project introduction, doc index, contribution guide, and on-call expectations
  - `docs/severity-levels.md` — draft severity rubric (SEV-1 … SEV-4)
  - `docs/escalation-paths.md` — draft escalation ladder and contacts template

## 2. Epic and Sub-issues

**Epic: Incident response runbook coverage** — issue #4
https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/issues/4

Exactly three sub-issues are linked underneath it:

| # | Title | Link |
|---|-------|------|
| #5 | Runbook: total service outage | https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/issues/5 |
| #6 | Runbook: failed deployment | https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/issues/6 |
| #7 | Runbook: data restoration | https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/issues/7 |

A comment naming all three sub-issues and linking the documentation pull request was posted on the epic and verified present in its comment thread:
https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/issues/4#issuecomment-6319089140

## 3. Documentation Pull Request

- **Title:** Add on-call rotation page to docs
- **PR:** #8 — https://github.com/mcpmark-eval-liuhezi/incident-response-playbook/pull/8
- **Branch:** `docs-oncall` → `main`
- **Adds:** `docs/oncall-rotation.md` with a six-week draft rotation table, handoff expectations, and an onboarding checklist
- **Review comments:** none — the PR currently has no review comments and no submitted reviews.

## 4. Team Findings

- **Organization membership:** `mcpmark-eval-liuhezi` (https://github.com/mcpmark-eval-liuhezi)
- **Teams:** none. The account does not belong to any organization teams, so there are no team members to list.

## About this file

This status summary was intended to be saved as a gist. The access token in use cannot create gists (HTTP 403 — "Resource not accessible by personal access token"), so the summary is persisted in this repository file instead, under the requested name `kickoff-status.md`.

## Summary

All requested items are in place, with two deviations driven by token permissions: (1) the repository lives under the `mcpmark-eval-liuhezi` organization rather than the personal account, and (2) this status summary is a repository file rather than a gist. Issue and pull-request numbering starts higher than expected (#4, #5–#7, #8) due to pre-existing items in the repository (an earlier Log4Shell tracking issue #2 and a draft PR #3).
