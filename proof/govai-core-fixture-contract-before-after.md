# GovAI Core Fixture Contract - Public Before / After

This is a public proof asset for Mary Wang's audit artifact work.

It is not a paid client case study. It is not a testimonial. It is a public open-source contribution record.

## Public Links

- Issue context: https://github.com/MonikaDvorackova/govai-core/issues/31
- Merged PR: https://github.com/MonikaDvorackova/govai-core/pull/108
- Follow-up implementation issue: https://github.com/MonikaDvorackova/govai-core/issues/110

## Before

The project had a signed audit export verifier direction, but downstream consumers needed a clearer fixture contract:

- which verifier stages should exist;
- which failures should be stable enough for external tools;
- how serialized output should be checked;
- how CI and humans should know the report is complete;
- how the contract relates to future Rust verifier output.

The first PR version also did not satisfy all repository workflow requirements:

- wrong target branch;
- missing required report under `docs/reports/`;
- remote checks reported branch-policy and evidence/report failures.

## Mary Wang Actions

Mary narrowed the contribution to a documentation and report artifact:

1. Proposed a fixture contract for signed audit export verifier behavior.
2. Added the required repository report.
3. Retargeted the PR to `staging`.
4. Inspected remote GitHub Actions logs.
5. Identified stale base-`main` CI failures after the PR had already been retargeted.
6. Triggered fresh checks after the retarget.
7. Kept the PR scoped to the contract and report instead of expanding into implementation.

## After

The PR was merged.

The merged artifact gave the project a clearer foundation for:

- staged verifier output;
- stable reason codes;
- deterministic serialized coverage;
- fixture-per-reason-code validation;
- downstream compatibility testing;
- follow-up implementation alignment in the Rust verifier.

Remote checks passed, including:

- branch policy;
- compliance report presence;
- report gate;
- report content;
- make verify;
- evidence pack;
- security scan;
- supply-chain audit;
- GovAI CI.

## What This Proves

This public work shows Mary can:

- turn a vague audit/verifier need into a scoped artifact contract;
- satisfy a repository's evidence/report workflow;
- inspect CI logs instead of guessing;
- repair contribution workflow mistakes;
- keep scope tight until the artifact is accepted;
- communicate clearly with maintainers.

## What This Does Not Prove

- It does not prove paid customer demand.
- It does not claim the maintainer is a client.
- It does not claim legal, compliance, or security certification.
- It does not imply Mary owns or maintains GovAI Core.

## How This Maps To The Paid Offer

The paid Evidence Pack Triage uses the same operating pattern on a buyer's artifact:

1. Read one concrete artifact.
2. Identify what it proves.
3. Identify what it does not prove.
4. Find missing fields and ambiguity.
5. Recommend a reviewer-safe next version.
6. Suggest the smallest useful build or cleanup.
