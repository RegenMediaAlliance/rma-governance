# RMA Governance Change Flows

Each file here defines a **flow** — how a part of this repo is changed. Collectively
they are RMA's *meta-governance* (the change process for the governance design).

## RMA adopts Quorum 1's Q-Git flow

RMA **chooses** to adopt [Q1's Q-Git change-flow](https://github.com/quorum1/governance/blob/main/flows/q-git.md)
as its base change process, because it's proven and keeps the two orgs legible to
shared members. Adapted to RMA's scale and independence:

- **`main` = the current Live Release.** Releases are numbered (Release 0, 1, 2…).
- **No direct commits to `main`.** Changes are made in a Working Release branch, then a
  pull request, then reviewed and approved before merge.
- **Consent-based approval** (Integrative Decision-Making): a change advances when there
  are no reasoned objections that it would harm RMA's purpose.
- **Strong-steward posture while small:** during this early "informal" phase, a single
  highly-trusted maintainer (the **Point**) may veto changes but cannot unilaterally
  enact them — the open-source "chief maintainer" model. This sunsets as RMA formalizes
  its Point + Triad and full Steward review.
- **Audit trail:** the history of this repo is RMA's public governance record. Live and
  legacy Releases are permanent and unaltered.

## Scopes

Any change to the repo must comply with all applicable flows.

- **Base flow (this readme):** scope = all changes, unless a more specific flow applies.
- *(Future RMA-specific flows — e.g. for the economic-model or member-rights — will be
  added here with their scopes, mirroring Q1's `flows/` pattern.)*

> Release 0 is fast-tracked (it emerges from prior drafting work). Full Steward review
> + member review steps are adopted as the alliance names its Point + Triad.
