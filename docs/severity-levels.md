# Severity Levels (Draft)

Draft definitions for classifying incidents. Once reviewed, this page becomes
the authoritative severity rubric for the on-call rotation.

| Level | Name | Customer impact | Target response |
| ----- | ---- | --------------- | --------------- |
| SEV-1 | Critical outage | Service down or data loss for all or most customers | Page primary on-call immediately; escalate to engineering lead after 15 min |
| SEV-2 | Major degradation | Core feature broken or severe latency for many customers | Page primary on-call; open incident channel |
| SEV-3 | Partial degradation | Non-core feature broken or a small group affected | On-call triages during business hours; ticket, not page |
| SEV-4 | Cosmetic / minor | Minor bugs, typos, internal tooling rough edges | File an issue; handle in normal sprint work |

## Classification rules (draft)

- If you are debating between two levels, pick the higher one.
- Severity can be raised or lowered as the picture becomes clearer; record the
  change and the reason in the incident thread.
- Severity is about **customer impact**, not about how worried you are.
