# Design Review Skill

name: design-review
use when: reviewing a MYOFFICESHOP screen before shipping

## Inputs
- The screen or screenshot
- day-one.md
- skills/design-principles/SKILL.md
- skills/specs/SKILL.md
- never-list.md

## Review
1. Can the user immediately identify the product and quantity?
2. Is the next action obvious?
3. Is it clear that purchase continues on eMAG?
4. Are all visible facts verified?
5. Does the screen follow the existing visual source of truth?
6. Is there any unnecessary step or competing CTA?

## Required output
- PASS or FAIL for each question
- One concrete failure if any
- One concrete fix
- One mechanic explicitly refused

## Review result for current landing-page direction
- Product/quantity clarity: PASS
- Next action: PASS
- eMAG destination clarity: PASS in intent, but the exact target URL for every product must be verified before publishing
- Visible factual claims: FAIL — the README says some CONFIG values and product URLs are still placeholders
- Visual consistency: PASS against the current index.html source values
- Unnecessary/competing CTA: PASS for the current direction

### One fail to fix first
Verify every CONFIG value and every product URL before treating the page as production-ready.

### Refused mechanic
Do not add an on-site checkout or a second primary purchase path that competes with the eMAG CTA.
