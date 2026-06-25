# Channel Review - 2026-06-25

## Verdict

The post-pivot motion is improving, but still has not crossed into qualified lead territory. The funnel now has direct sample requests, but no one has shared an artifact.

## Search Terms To Keep

- multi-standard compliance dashboard
- healthcare compliance dashboard evidence
- control evidence row
- evidence matrix dashboard
- audit evidence dashboard
- compliance evidence dashboard

These terms are closer to owner-operated dashboards and reviewable artifacts.

## Search Terms To Reduce

- generic SOC2 self-attestation
- Vanta Drata export in large repos
- broad evidence export in major public repos

Reason: Firecrawl produced a sample request but the issue closed with no artifact and a negative anti-agent response. It is not worth repeating this pattern in large repos unless the owner is explicitly asking for artifact review.

## Lead Handling Change

Prioritize owner engagement over repo size. A smaller repo where the owner replies and can share a row, screenshot, export, or checklist is more valuable than a large repo issue that only allows a public comment.

## Next Search Pattern

Use queries that imply a concrete artifact exists:

- `"compliance dashboard" "evidence_source"`
- `"control_id" "evidence_owner"`
- `"audit evidence dashboard" "gap_reason"`
- `"HIPAA" "evidence matrix"`
- `"ISO27001" "evidence dashboard"`

## Conversion Rule

Do not mention RMB399 until a lead shares a concrete artifact sample. If MedBrains shares a control row, dashboard screenshot, schema, or matrix, move it to `qualified` and offer Evidence Pack Triage.
