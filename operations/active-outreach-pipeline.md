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

- `AI workflow automation`
- `workflow audit`
- `AI automation landing page`
- `non technical founder automation`
- `n8n small business workflow`
- `agent activity log`
- `workflow builder`

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

## Revenue Rule

The website is only useful if it converts attention created elsewhere. If a day has zero public replies, the revenue loop did not run that day.
