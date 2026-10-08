# UnitCue Support — Project State

## Current phase
Static public support/privacy companion site for UnitCue.

## Working now
- Static `index.html`, `support.html`, `privacy.html`, and `.nojekyll` are present.
- This repository is not the primary application codebase.
- Preventive support disclosure update is prepared on `codex/unitcue-public-issue-disclosure-20261008`: GitHub Issues are identified as public, users are told not to include personal or sensitive details, and no private channel is offered because none was found in the site or canonical app repository.

## Current blockers
- Support/privacy wording must stay synchronized with actual UnitCue behavior and App Store disclosures.
- The disclosure change is in a review branch; it is not yet published.

## Next highest-value work
1. Review and merge the support disclosure PR, then verify the published static pages.
2. Reconcile wording with the canonical app repo if app behavior/disclosures change.

## Important decisions
- Canonical app repo is `Mikes-hub-va/pricebook-ios`.
- Avoid publishing personal contact details by default.
- Preserve existing privacy claims while warning users about public support issues.
