# CNJ Builders — Business Systems Reference

Last reviewed: 2026-11-10. Update this file when any fact below changes.

## Company
- CNJ Builders, residential general contractor, founded 2022. Office in Rothesay, NB, serving Greater Saint John.
- Usually 5–10 active projects.
- Team: Chris Jeffries (President), Nic Jeffries (VP Operations: estimating, business development), Ross (Field Project Coordinator), Carly (Project Coordination & Drafting), Tyler (Site Supervision / Carpenter).

## Systems and source of truth
| System | Used for | Source of truth for |
|---|---|---|
| QuickBooks Online | Accounting; each job is a QBO Project | Official financials, job actuals |
| JobTread | Estimates, budgets, change orders, POs, progress, documents | Project status, scope, COs |
| busybusy | Time tracking | Second check on direct labour hours |
| Microsoft 365 (via GoDaddy) | Business email (cnj@cnjbuilders.com) | — |

## Job costing rules
- Actuals are recorded at cost, no markup.
- Direct labour cost = $30/hr (wage).
- Own-crew labour is charged to jobs at ~$90/hr. Subbed finish work (trim, flooring, tile, cabinetry) can run ~$50/hr, so finish work is often subbed out.
- From Nov 2026, bills are entered in QBO with a JobTread cost code on every line, starting with the 10 McNamee and 42 Cedar jobs.

## KPI
- Job profit ÷ direct labour cost
  - Target: 250%
  - Floor: 180%. Any job below this gets flagged and reviewed.

## Supplier terms
| Supplier | Terms |
|---|---|
| Kent | Due 60 days after end of purchase month |
| Home Hardware KV / Hampton | Due 60 days after end of purchase month |
| Home Hardware Loch Lomond | Due 30 days after month-end |
| All other credit suppliers | Due 30 days after month-end |

## Subcontract agreements
- Sub Agreement A (TEMP-OPS-006): larger subcontracts
- Sub Agreement B (TEMP-OPS-007): subs under $40K per job
- Payment stages, holdback and PO rules: see `reference/sub-agreements.md`.

## Cost codes
- Full JobTread cost code list: `reference/cost-codes.csv` (exported 2026-11-02).
- 32 parent codes (0000–3100), each with three sub-codes: x10 Labour, x20 Materials, x30 Subcontractor. Only sub-codes map to QBO items.

## Payroll
- Weekly, processed Sunday.

## Tax and legal
- HST 15% (NB).
- NB Construction Remedies Act holdbacks apply (10% statutory holdback on subs; see `reference/sub-agreements.md`). Confirm current holdback % and release timing with the accountant/lawyer before relying on them.
