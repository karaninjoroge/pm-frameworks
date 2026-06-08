# RICE Prioritization Framework

**Category:** Prioritization
**Best For:** Comparing features or initiatives that serve different user segments with different levels of effort

---

## What It Is

RICE is a scoring framework that helps PMs prioritize features by quantifying four factors:

- **R — Reach:** How many users will this affect in a given time period?
- **I — Impact:** How much will this move the needle for each user it reaches?
- **C — Confidence:** How confident are you in your reach and impact estimates?
- **E — Effort:** How many person-months will this take to build?

**RICE Score = (Reach × Impact × Confidence) / Effort**

Higher score = higher priority.

---

## When to Use It

- You have a backlog of features and need to rank them objectively
- Stakeholders are debating priorities based on gut feel rather than data
- You want to depoliticize a prioritization conversation with a structured method
- Features serve different user segments and are hard to compare intuitively

---

## When NOT to Use It

- You have only 2–3 options to choose from (just make the call)
- All features are roughly equal in effort and reach (RICE adds false precision)
- You are in early discovery and do not yet know what to build (RICE is for ranking, not finding)
- Leadership has already committed to a direction — use RICE to sequence within it, not to reverse it

---

## How to Apply It

**Step 1 — Define your time period**
Choose one consistent period for Reach estimates (usually monthly or quarterly).

**Step 2 — Estimate Reach**
How many users will encounter this feature in your time period? Use data where available, honest estimates where not.

**Step 3 — Estimate Impact**
Use a fixed scale:
- 3 = massive impact per user
- 2 = high impact
- 1 = medium impact
- 0.5 = low impact
- 0.25 = minimal impact

**Step 4 — Estimate Confidence**
- 100% = you have data to support your estimates
- 80% = you have some evidence
- 50% = mostly a gut call
- Never use 100% unless you have validated research

**Step 5 — Estimate Effort**
Person-months required across the whole team. Be honest — teams systematically underestimate effort.

**Step 6 — Calculate and rank**

---

## Example (Hospital Queue Management)

| Feature | Reach | Impact | Confidence | Effort | Score |
|---|---|---|---|---|---|
| SMS queue updates | 2000/mo | 3 | 80% | 2 | 2,400 |
| Staff dashboard | 10/mo | 3 | 90% | 4 | 67.5 |
| Appointment booking | 2000/mo | 2 | 50% | 10 | 200 |

SMS updates score highest — correctly so. They reach the most users, have high impact per user, and are relatively simple to build.

---

## Common Mistakes

**Inflating confidence:** PMs want their favorite features to win, so they set confidence at 100%. If you have not done research, your confidence is 50% at most.

**Ignoring effort:** Features that score well on reach and impact but require 12 months of engineering should not be in your next sprint. Effort is a denominator for a reason.

**Treating the score as final:** RICE is a starting point for a conversation, not a command. If a lower-scoring feature has strategic importance not captured in the model, say so explicitly.

---

## Template

| Feature | Reach | Impact | Confidence | Effort | RICE Score | Priority |
|---|---|---|---|---|---|---|
| [Feature 1] | | | | | | |
| [Feature 2] | | | | | | |
