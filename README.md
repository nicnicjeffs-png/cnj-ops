# CNJ Ops

CNJ Builders' operating playbook: Claude instructions, reference data and SOPs.
One source of truth. Change it here, note it in CHANGELOG.md, then re-sync any Claude Project that uses it.

## Structure
| Folder | What goes here |
|---|---|
| `instructions/` | Instructions for Claude Projects (paste into, or sync to, the Project) |
| `reference/` | Stable facts: systems, supplier terms, labour rates, KPIs, agreements |
| `sop/` | Step-by-step routines the team follows |

## Files
- `instructions/jt-qbo-audit.md`: JobTread + QuickBooks setup and audit project
- `reference/business-systems.md`: systems, source-of-truth rules, terms, rates, KPIs
- `sop/weekly-cashflow-check.md`: Monday cash-flow and sync check
- `sop/month-end-job-review.md`: monthly job-cost review
- `sop/document-entry.md`: where each document type is entered (one entry point)

## Rules for editing
1. Edit on github.com (pencil icon) or upload a new version.
2. Write a short commit message saying what changed and why ("Added approval rule for $ changes").
3. Add a line to CHANGELOG.md.
4. Re-sync the Claude Project knowledge.

Don't put tasks, job documents, client info or passwords here. Those stay in JobTread, QuickBooks and your password manager.
