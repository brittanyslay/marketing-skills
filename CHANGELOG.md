# Changelog

## v1.1.0 - 2026-11-05

A sharper pass on all eight skills. Same eight jobs, better execution.

- Every skill is now intake-first and does the work: it asks the few things it needs (or reads the URL, doc, or export you point it at), assumes sensible defaults, and proceeds, instead of making you assemble inputs or hand-write the prompt.
- Every skill runs an internal critique loop against a stated quality bar before it hands anything back, so you are the manager reviewing a strong draft, not the editor fixing a weak one.
- Added a copy scanner for the anti-robot editor (`skills/anti-robot-editor/scan.py`): it scores copy for em and en dashes, banned words and phrases, negation-pivot cadences, and sentence rhythm, and exits non-zero while any hard tell remains. Standard library only, with a `--selftest`. The editor now revises against it in a loop until the copy reads CLEAN.
- Added a compact worked example to each skill so the bar is visible.
- No change to the eight skill names, the license, or the noncommercial terms.

## v1.0.2 - 2026-08-20

Pulled the README preview image for now while all the public repos' preview images get reconsidered together. The image file is still in the repo, just not linked from the README.


## v1.0.1 - 2026-08-20

Added a caption clarifying the README preview image (docs/anti-robot-editor.png) shows the skill's actual before/after output, not a decorative illustration - matching the same "show it real, not a mockup" standard applied across the other public skill repos.

## v1.0.0 - 2026-07-16

Initial release: eight reusable AI skills for B2B marketing (anti-robot-editor, positioning-in-five-seconds, icp-from-best-customers, competitive-teardown, first-demand-plan, cold-outreach, content-engine, case-study-from-a-win).
