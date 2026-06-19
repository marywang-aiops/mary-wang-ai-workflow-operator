# Active Outreach Pipeline

The website is not the acquisition engine. It is the place prospects land after Mary has been useful somewhere else.

## Daily Target

- Find 10 relevant conversations.
- Leave 3 useful public replies.
- Track every reply in `leads/lead-tracker.csv`.
- Follow up after 24-48 hours when someone responds.
- Review `operations/daily-scoreboard.md` at the end of the day.

## Where To Look

### GitHub

Search for:

- `audit artifact`
- `machine-readable audit`
- `audit manifest`
- `workflow handoff`
- `human approval gate workflow`
- `review gate docs`
- `local-control audit output`
- `auditor-ready evidence pack`
- `approval decision audit`
- `redacted audit evidence`

Good targets:

- issues asking for implementation help
- roadmap issues about workflow/agent features
- awesome lists accepting tool suggestions
- hiring posts asking for AI workflow people

Avoid:

- unrelated bugs
- bot-generated issue spam
- closed issues
- repos where maintainers clearly do not want promotion

### Reddit

Search subreddits:

- `r/n8n`
- `r/automation`
- `r/SaaS`
- `r/Entrepreneur`
- `r/smallbusiness`
- `r/indiehackers`
- `r/nocode`

Good targets:

- people asking whether AI automation is worth selling
- founders confused about workflow automation
- small business owners describing repeated admin work
- people comparing n8n/Zapier/custom build

Avoid:

- posting links as first touch
- generic self-promo threads unless explicitly allowed
- arguing about AI hype

### Xiaohongshu / Zhihu

Search topics:

- `AI 自动化`
- `工作流`
- `不会写代码`
- `AI 工具`
- `创业者 效率`
- `n8n`
- `AI agent`

Good targets:

- comment with a checklist
- answer practical questions
- point to email only when someone asks for help

## Reply Formula

1. Start with the specific problem in the thread.
2. Give a 3-5 point diagnostic checklist.
3. Say what to do first.
4. Link to Mary Wang only if the link genuinely helps.

## Good Public Reply Pattern

```text
I would not start by choosing the tool. I would first pin down the workflow boundary:

1. What is the repeated input?
2. What output should exist every time?
3. Which step must stay human-approved?
4. What would make the automation unsafe or unreliable?

The smallest useful build is usually one workflow, one input type, one output artifact, and a review checklist. Once that works, then it is worth deciding between n8n, Zapier, custom code, or an agent.
```

## CTA Rules

Use a CTA only when the user is clearly asking for help:

```text
I maintain a small AI workflow audit checklist here if useful: https://github.com/marywang-aiops/mary-wang-ai-workflow-operator
```

or:

```text
If you want a second pair of eyes, email 939172168@qq.com with one sample input and the output you wish you had.
```

## Current Posted Replies

| Date | Platform | URL | Purpose |
| --- | --- | --- | --- |
| 2026-05-20 | GitHub | https://github.com/jenishkafle777-web/AgenticAI/issues/3#issuecomment-4494335097 | Landing page/intake advice |
| 2026-05-20 | GitHub | https://github.com/siddharth23P/nox/issues/48#issuecomment-4494338570 | Workflow agent auditability advice |
| 2026-05-20 | GitHub | https://github.com/activepieces/activepieces/issues/13231#issuecomment-4494341599 | AI workflow engineer opportunity |
| 2026-05-20 | GitHub | https://github.com/ATHARVA262005/ai-audit-shelf/issues/1#issuecomment-4495048118 | AI audit/versioning docs contribution angle |
| 2026-05-20 | GitHub | https://github.com/hkuwana/hiroPersonalSite/issues/74#issuecomment-4495050387 | AI workflow audit offer positioning |
| 2026-05-20 | Reddit | https://www.reddit.com/r/n8n_ai_agents/comments/1tfkf0j/comment/omtg6e2/ | Paid-service path for small-business AI automation |
| 2026-05-24 | GitHub PR | https://github.com/ATHARVA262005/ai-audit-shelf/pull/19 | Operator-facing audit UX guide after maintainer engagement |
| 2026-05-28 | GitHub | https://github.com/nestharus/agent-core/issues/174#issuecomment-4560212375 | Audit gate manifest and `apply-gate-set` operator advice |
| 2026-05-30 | GitHub | https://github.com/magicxiaomin/dramadev/issues/11#issuecomment-4581293489 | Review gate docs contract and `needs-split` handling |
| 2026-05-31 | GitHub | https://github.com/lucpez/cloudporter/issues/27#issuecomment-4585431754 | Machine-readable audit finding schema and stable rule IDs |
| 2026-06-02 | GitHub | https://github.com/lucpez/cloudporter/issues/27#issuecomment-4598088875 | Follow-up on optional remediation fields and suppression IDs |
| 2026-06-04 | GitHub | https://github.com/oscharko-dev/Keiko/issues/186#issuecomment-4618321099 | Governed workflow handoff contract fields and consumer question |
| 2026-06-05 | GitHub | https://github.com/victorlavrenko/answer-engineering/issues/19#issuecomment-4627493276 | Reviewable compliance audit artifact schema and redaction tests |
| 2026-06-05 | GitHub | https://github.com/coastalgit/solution-os/issues/27#issuecomment-4627494398 | Local-control audit output fields and leakage warning fixture tests |
| 2026-06-05 | GitHub | https://github.com/dativo-io/talon/issues/147#issuecomment-4630401788 | HITL approval-gate evidence records and deterministic deny/timeout tests |
| 2026-06-06 | GitHub | https://github.com/oscharko-dev/Keiko/issues/536#issuecomment-4638198966 | Redacted relationship audit model and durable/transient state split |
| 2026-06-06 | GitHub | https://github.com/ManicodeSecurity/trust-me-bro/issues/31#issuecomment-4638199606 | Review-gated scanner outputs and audit/refutation evidence invariants |
| 2026-06-07 | GitHub | https://github.com/writer/aperio/issues/49#issuecomment-4642149291 | Auditor-ready evidence pack manifest, redaction, and incomplete-evidence test |
| 2026-06-07 | GitHub | https://github.com/steffenboe/NclaveAI/issues/18#issuecomment-4642150327 | Approval-aware audit log event split and deletion-invariant tests |
| 2026-06-08 | GitHub | https://github.com/dativo-io/talon/issues/147#issuecomment-4647734768 | Follow-up on approval lifecycle fixture and reviewer-facing audit story |
| 2026-06-08 | GitHub | https://github.com/DariuszNewecki/CORE/issues/525#issuecomment-4647742172 | Signed Solo-tier audit export pack boundary and negative fixture |
| 2026-06-09 | GitHub | https://github.com/DariuszNewecki/CORE/issues/525#issuecomment-4658665372 | Follow-up on buyer-readable verifier contract and F-46 fixture matrix |
| 2026-06-09 | GitHub | https://github.com/MonikaDvorackova/govai-core/issues/31#issuecomment-4658672865 | Rust-native signed audit verifier stages and negative completeness fixtures |
| 2026-06-09 | GitHub | https://github.com/oscharko-dev/Keiko/issues/484#issuecomment-4658673104 | Operator-facing runtime evidence manifest and redaction/degraded-mode tests |
| 2026-06-10 | GitHub | https://github.com/DariuszNewecki/CORE/issues/525#issuecomment-4668938965 | Follow-up asking for a tiny synthetic fixture export skeleton |
| 2026-06-10 | GitHub | https://github.com/blencorp/ashlar/issues/11#issuecomment-4668939425 | CI audit evidence bundle, verifier output, SARIF boundary, and negative fixtures |
| 2026-06-10 | GitHub | https://github.com/euphoricdoom/.Neon/issues/28#issuecomment-4668939823 | Proof packet facts/claims/limits schema and unsupported-claim negative fixture |
| 2026-06-11 | GitHub | https://github.com/DariuszNewecki/CORE/issues/525#issuecomment-4676522556 | Follow-up on F-46 context-summary boundary and governed-change leak canary |
| 2026-06-11 | GitHub | https://github.com/madmax983/egregore/issues/68#issuecomment-4676526612 | Redaction-safe evidence bundle verifier verdicts and protected-payload negative fixtures |
| 2026-06-11 | GitHub | https://github.com/safal207/ProofPath/issues/161#issuecomment-4676526780 | Portable payment-guard evidence bundle and offline verifier fixtures |
| 2026-06-12 | GitHub | https://github.com/oscharko-dev/Keiko/issues/186#issuecomment-4686677122 | Follow-up on remembered-context evidence references after PR #947 audit closure |
| 2026-06-12 | GitHub | https://github.com/Noetheon/vuln-prioritizer-cli/issues/29#issuecomment-4686677236 | HTML report vs evidence-bundle source-of-truth split and provenance negative fixtures |
| 2026-06-12 | GitHub | https://github.com/piyushgupta27/ai-sdlc/issues/86#issuecomment-4686677367 | Signed per-PR gate-evidence bundle layout and required-status verifier negative fixtures |
| 2026-06-13 | GitHub | https://github.com/DariuszNewecki/CORE/issues/525#issuecomment-4697097031 | Follow-up turning ADR-100 evidence-class boundary into governed-change leak fixture behavior |
| 2026-06-13 | GitHub | https://github.com/fermano/TC2/issues/90#issuecomment-4697103924 | Signed audit export URL redaction at persistence boundary and durable-log regression test |
| 2026-06-13 | GitHub | https://github.com/madmax983/egregore/issues/155#issuecomment-4697103926 | Complete JSONL backup export vs redaction-safe evidence bundle boundary |
| 2026-06-13 | GitHub | https://github.com/joeszilagyi/Upkeeper/issues/661#issuecomment-4697103923 | Sanitized JSONL missing primary-key identity cases and conflict-key regression fixture |
| 2026-06-14 | GitHub | https://github.com/MonikaDvorackova/govai-core/issues/31#issuecomment-4700407598 | Follow-up on stable verifier reason codes and fixture-per-code serialized VerificationResult snapshots |
| 2026-06-14 | GitHub | https://github.com/benseverndev-oss/goldenmatch-shell-company-network/issues/160#issuecomment-4700411308 | Machine-readable evidence dossier and publish gate for verification/defamation checklist |
| 2026-06-14 | GitHub | https://github.com/fderuiter/CRF.xl/issues/56#issuecomment-4700411295 | Reviewer-ready export DoD with manifest, verification report, regeneration, and mismatch fixture |
| 2026-06-14 | GitHub | https://github.com/quantam101/tradegate2/issues/10#issuecomment-4700411296 | Robinhood MCP durable-boundary redaction and keyed fingerprint guidance |
| 2026-06-14 | GitHub | https://github.com/jovillal/placamia/issues/67#issuecomment-4700411293 | Audit log key/value-shape redaction policy and nested regression fixture |
| 2026-06-15 | GitHub | https://github.com/MonikaDvorackova/govai-core/issues/31#issuecomment-4703914279 | Follow-up accepting a small contract-first verifier contribution scope |
| 2026-06-15 | GitHub PR | https://github.com/safal207/ProofPath/pull/164 | Added Evidence Bundle v0.1 fixture contract README |
| 2026-06-15 | GitHub | https://github.com/safal207/ProofPath/issues/161#issuecomment-4703913376 | Linked ProofPath fixture-contract PR back to the milestone issue |
| 2026-06-15 | GitHub | https://github.com/marctjones/pdfe/issues/466#issuecomment-4703918179 | PDF signature verification structured result states and trust-overclaim fixtures |
| 2026-06-15 | GitHub | https://github.com/equaltoai/lesser-body/issues/332#issuecomment-4703918181 | MCP tool result vs durable audit-log redaction boundary and nested bearer/JWT fixtures |
| 2026-06-16 | GitHub PR | https://github.com/MonikaDvorackova/govai-core/pull/108 | Added audit export verifier fixture contract doc |
| 2026-06-16 | GitHub | https://github.com/MonikaDvorackova/govai-core/issues/31#issuecomment-4714173807 | Linked GovAI Core fixture-contract PR back to verifier issue |
| 2026-06-16 | GitHub | https://github.com/syndicalt/rava/issues/122#issuecomment-4714178050 | Production audit export manifest, privacy class, tamper-evidence, and non-claim boundaries |
| 2026-06-16 | GitHub | https://github.com/pokekarten/igentic-iphone/issues/13#issuecomment-4714178043 | Typed policy reason-code serialization and smoke-test boundary |
| 2026-06-17 | GitHub | https://github.com/msaad00/agent-bom/issues/2929#issuecomment-4725253357 | Hosted evidence lake vs exported evidence manifest boundary, tenant isolation, diff stability, redaction, and retention tests |
| 2026-06-17 | GitHub | https://github.com/voltron-1/UIW-Cyber-Defence-Platform/issues/82#issuecomment-4725257625 | Fail-closed rule/SOP metadata contract, coverage denominator output, unmapped IDs, and no-demo-fallback tests |
| 2026-06-18 | GitHub | https://github.com/marctjones/pdfe/issues/466#issuecomment-4737175012 | Follow-up on signature trust validation release scope, trust-state matrix, and UI overclaim invariant |
| 2026-06-18 | GitHub | https://github.com/walter-robson/sportsml/issues/31#issuecomment-4737180945 | SOC2 evidence inventory, Type I vs Type II implementation framing, and traceable control evidence |
| 2026-06-18 | GitHub | https://github.com/stylusnexus/agent-armor/issues/24#issuecomment-4737182178 | Audit event record vs evidence package vs control claim split, package digest, and tamper/no-raw-content tests |
| 2026-06-19 | GitHub PR | https://github.com/MonikaDvorackova/govai-core/pull/108#issuecomment-4747787668 | Rebased PR to staging, added required audit report, changed PR base to staging, and replied with validation |
| 2026-06-19 | GitHub | https://github.com/Tr3kkR/Yuzu/issues/303#issuecomment-4747798112 | SOC2 control matrix plus evidence index row shape, evidence repository naming, freshness rules, and generated-finding boundary |

## Revenue Rule

The website is only useful if it converts attention created elsewhere. If a day has zero public replies, the revenue loop did not run that day.
