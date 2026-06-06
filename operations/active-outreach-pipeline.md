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

## Revenue Rule

The website is only useful if it converts attention created elsewhere. If a day has zero public replies, the revenue loop did not run that day.
