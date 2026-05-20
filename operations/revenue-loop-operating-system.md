# Revenue Loop Operating System

This is the operating system for turning Mary Wang from a static identity into a revenue loop.

North star:

> One paid AI Workflow Audit first, then convert the audit into a Mini Automation Build.

## Funnel

```text
Community problem found
  -> useful public reply
  -> profile / checklist visit
  -> email inquiry
  -> workflow sample received
  -> RMB 699 audit offered
  -> payment received
  -> audit delivered
  -> mini-build quoted
```

## Status Definitions

Use these exact statuses in `leads/lead-tracker.csv`.

| Status | Meaning | Next Action |
| --- | --- | --- |
| `sourced` | Found a relevant conversation, no reply yet | Decide whether to reply |
| `commented` | Mary left a useful public reply | Check for response in 24-48h |
| `engaged` | Someone replied, liked, or asked follow-up | Ask for one input sample and desired output |
| `qualified` | Person described a real workflow problem | Send audit scope confirmation |
| `audit-offered` | RMB 699 audit was offered | Follow up once after 24h |
| `paid` | Payment received | Deliver audit within 48h |
| `delivered` | Audit delivered | Ask about mini build |
| `mini-build-quoted` | Build quote sent | Follow up after 48h |
| `closed-won` | Audit or build completed and paid | Ask for anonymized case study permission |
| `closed-lost` | Not a fit or no response after follow-up | Record reason |

## Daily Operating Cadence

Every day at 10:00:

1. Check existing leads for replies.
2. Follow up only when there is a real reason.
3. Find 10 relevant conversations.
4. Leave 5 useful comments or replies.
5. Record all actions in `leads/lead-tracker.csv`.
6. Add a short note to `leads/outreach-log.md`.

Minimum daily output:

- 10 sourced conversations
- 5 useful public replies
- 1 Chinese post/comment draft or published comment
- 0 fake claims
- 0 low-value link drops

## Three-Day Review

Every three days, check:

- Which search terms produced real discussions?
- Which replies got responses?
- Which channel produced the highest-intent people?
- Did any reply feel like spam?

Decision rules:

- If a search term produces mostly bot posts or irrelevant issues, remove it.
- If a reply gets engagement, turn it into a reusable content asset.
- If a channel produces no engaged leads after 15 useful replies, reduce effort by half.
- If a channel produces qualified leads, double the reply volume there.

## Seven-Day Review

Metrics:

| Metric | Target |
| --- | --- |
| Useful public replies | 25+ |
| Engaged leads | 3+ |
| Qualified leads | 1+ |
| Audit offers sent | 1+ |
| Paid audits | 0-1 |

Decision rules:

- If replies are below 25, execution volume is the bottleneck.
- If replies are high but engagement is zero, targeting or reply quality is wrong.
- If qualified leads exist but no audit offers are accepted, trust/offer clarity is wrong.
- If payment happens, stop broad experimentation and document the case study.

## Fourteen-Day Review

Goal:

- One paid audit, or
- Five qualified leads, or
- A clear decision to change the wedge.

If no qualified leads:

- Narrow the target buyer.
- Try one of these wedges:
  - `AI workflow audit for n8n builders`
  - `AI workflow audit for solo service businesses`
  - `AI folder/repo inspection for non-technical founders`
  - `AI client-reporting workflow for consultants`

If qualified leads but no payment:

- Add a better sample audit.
- Offer first-client price: RMB 399 for anonymized case study permission.
- Shorten scope to a 24-hour mini audit.

If payment:

- Deliver within 48 hours.
- Ask permission for anonymized before/after.
- Quote Mini Automation Build within 24 hours after delivery.

## Thirty-Day Review

Goal:

- 100 useful public interactions
- 1-3 paid audits
- 1 mini-build quote sent
- 1 anonymized case study published

Decision:

- Continue current offer if it produced payment or qualified demand.
- Reposition if there were conversations but no buyer urgency.
- Stop a channel if it produced no engaged leads after 30 quality comments.

## Offer Ladder

1. Free public checklist.
2. RMB 699 AI Workflow Audit.
3. RMB 1999-4999 Mini Automation Build.
4. RMB 6999+ Monthly AI Ops Retainer.

Do not push the higher offer until the user has a clear workflow and has seen useful work.

