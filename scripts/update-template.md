# Update Workflow

How job lists in `data/` should be updated.

## Cadence

- Weekly batch update on Mondays.
- Hot-fix removals (broken or expired links) any day.

## Per-update checklist

1. Open the relevant `data/*.md` file.
2. Add new rows at the top, under the header row.
3. Update the `Last updated:` line at the top of the file.
4. Remove rows where the apply link is dead or the role is filled.
5. Open a PR titled `update YYYY-MM-DD: <area>` (e.g. `update 2026-07-07: internships`).

## Row format

| Company | Role | Location | Type | Apply Link | Date Added | Notes |
|---|---|---|---|---|---|---|

- `Type` is one of: `Internship`, `Full-time`, `Co-op`, `Contract`.
- `Date Added` is `YYYY-MM-DD`.
- `Notes` should be short. Keep recruiter pitches out.

## Source rules

- Apply link must go to the company's own careers page when possible.
- No aggregator tracking URLs.
- No copy/pasted full job descriptions. Link out instead.
