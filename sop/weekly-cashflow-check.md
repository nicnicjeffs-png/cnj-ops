# SOP — Weekly Cash-Flow & Sync Check

**When:** Every Monday morning (before payables run)
**Owner:** Nic (Claude runs the check, Nic approves any action)
**Time:** ~15 min

## Steps
1. **Sync health:** In JT, check the QBO integration for sync errors and the *Draft/Unsynced* view. Anything stuck more than 2 days gets fixed or escalated.
2. **Cash out:** Open *Cash Out – Bills Due*. List bills due in the next 14 days with totals by week. Remember Kent / HH KV-Hampton are 60 days after end of the purchase month.
3. **Cash in:** Open *Cash In – Open Invoices*. List anything overdue and assign a follow-up owner and date.
4. **Change orders:** Open *Pending Change Orders*. Anything waiting on a client more than 7 days gets a follow-up.
5. **Net position:** Cash in expected (next 14 days) minus cash out due (next 14 days), plus payroll (weekly, Sundays). Flag if negative.

## Output (Claude)
- 3-line summary: net 14-day position, biggest risk, action needed
- Table: Item | $ | Due | Action | Owner
- No changes made without Nic's approval
