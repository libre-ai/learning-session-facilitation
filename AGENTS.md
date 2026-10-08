# learning-session-facilitation Canonical Agent Rules

## Purpose

Reserved couche-1 product home for Libre AI Learning Session Facilitation:
prepare and follow a learning session with cited source material,
participant roles and responsibilities.
Doctrine lives upstream: https://raw.githubusercontent.com/libre-ai/project-governance/HEAD/AGENTS.md

## Domain doctrine

- Source material stays cited; delegated tasks stay explicit per participant.
- `project.v1.yaml` is the authority on project state and admission
  criteria; the README "Project status" section is generated from it —
  never edit that section by hand.
- Recovered code (`apps/sessions`) is not product qualification.
- Contract shapes are canonical in `libre-ai/schemas-and-contracts`, consumed
  pinned, never redefined here.

## Commands

- Prepare the pinned composition (target `learning-session-facilitation`):
  https://raw.githubusercontent.com/libre-ai/project-governance/HEAD/docs/LOCAL-COMPOSITION.md
- `bun run check` from this repository's root in the composition.

## Working here

- Security > quality > performance > completeness, in that order on conflict.
- Check real state before editing: `git status --short` and the check above;
  never hide a red test.
- English for code, comments and this file.
- Never commit a machine-local absolute filesystem path, a secret or a
  personal identifier.
