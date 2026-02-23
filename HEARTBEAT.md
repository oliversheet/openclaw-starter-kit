# HEARTBEAT.md

<!-- 
Your AI reads this on every heartbeat poll.
Keep it small — scripts are free, model time is expensive.
Add checks, reminders, and periodic tasks here.
-->

## Checks

<!-- Example: run scripts that return output only when something needs attention -->
<!-- 
```bash
/path/to/your/check-email.sh
/path/to/your/check-calendar.sh
```
-->

## Memory maintenance (once per day)
If today's date is different from "Last updated" in MEMORY.md:
1. Read recent `memory/YYYY-MM-DD.md` files
2. Update MEMORY.md with anything significant
3. Remove outdated info
4. Update the "Last updated" date

## If nothing needs attention
Reply: HEARTBEAT_OK

---

**Philosophy**: Scripts are free. Model time is expensive.
Don't burn tokens deciding "nothing happening" — let scripts decide that.
