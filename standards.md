# RMA Governance Repo Standards

Guidelines for the contents of this repository. Draft — will evolve as the repo grows.
Adapted from [Quorum 1's repo standards](https://github.com/quorum1/governance/blob/main/standards.md).

## Inter-file links & shared terms

- Direct links between repo files should be used only when the cited file is a
  **critical dependency** of the referring file. When used, place the link once, near
  the top (just under the header, or in a "Key Dependencies" section).
- For all other shared terms, define them in [`docs/glossary.md`](docs/glossary.md) and
  link to the glossary header. The glossary is an automatic dependency of every file.

## Status markers

Every open or unfinished section carries an explicit marker so readers (and the
Wednesday call) can see state at a glance:

- `[OPEN]` — not yet drafted; awaits alliance input.
- `[DRAFT]` — drafted, not yet ratified.
- Ratified content carries no marker (it's live by virtue of being merged to `main`).

## Distribute-as-is discipline

Per Ed (2026-06-29): get material in front of members for feedback rather than
perfecting it first. A clearly-marked `[OPEN]` stub in members' hands beats a polished
doc nobody has seen. Don't let "not finished" block "shared."

## Tone

Plain language over jargon. The earlier charter drafts carried heavy abstraction; the
live versions favor what a new member can read once and understand.
