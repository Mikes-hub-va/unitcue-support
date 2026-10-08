# UnitCue Support — Handoff

## Objective
Keep UnitCue's static support/privacy pages aligned with the app and clearly disclose public support channels.

## Current state
`support.html` on branch `codex/unitcue-public-issue-disclosure-20261008` warns that GitHub Issues and replies are public, discourages personal/sensitive details, and notes that the site does not list a private support channel. No approved private channel was found in site or canonical app repo context. Privacy copy and app behavior claims are unchanged.

## Relevant files
`support.html`, `privacy.html`, `index.html`, `AGENTS.md`, `docs/PROJECT_STATE.md`.

## Completed work
Source checks passed for all local page links and the public issue destination. The privacy page's existing privacy claims and support link are preserved.

## Next action
Review and merge the pull request, then verify the published static pages and links.

## Validation
Fetched the branch versions of all three static pages; local links resolve among the site files, the support link targets the repository's public Issues URL, and the disclosure text is present.

## Blockers / owner actions
Publication requires normal pull request review and merge. No owner contact information was added.
