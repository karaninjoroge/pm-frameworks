# RICE Prioritisation Framework

> **Category:** Prioritisation | **When to use:** When you have a backlog of features and need to rank them objectively

---

## What Is RICE?

RICE is a scoring framework that helps PMs prioritise features by calculating a single comparable score for each item.

**RICE = (Reach × Impact × Confidence) / Effort**

| Variable | What it measures | How to score |
|---|---|---|
| **Reach** | How many users affected per time period | Number of users/month |
| **Impact** | How much does it move the needle per user | 3=massive, 2=high, 1=medium, 0.5=low, 0.25=minimal |
| **Confidence** | How confident are you in your estimates | 100%=high, 80%=medium, 50%=low |
| **Effort** | Person-months to build | Estimate in person-months |

---

## When to Use It

✅ You have 5+ competing features or initiatives
✅ You need to justify prioritisation decisions to stakeholders
✅ You want to remove personal bias from the prioritisation process
✅ You're preparing a roadmap and need a defensible ordering

❌ When you have very little data (estimates become guesswork)
❌ When all items are roughly equal in scope
❌ As a substitute for strategic thinking — RICE ranks options, it doesn't create them

---

## Applied Example — Hospital Queue Management Platform

| Feature | Reach | Impact | Confidence | Effort | RICE Score |
|---|---|---|---|---|---|
| USSD check-in | 350 patients/day | 3 (massive) | 80% | 3 person-months | **280** |
| SMS reminders | 350 patients/day | 2 (high) | 90% | 1 person-month | **630** |
| Staff dashboard | 8 staff/day | 3 (massive) | 70% | 2 person-months | **84** |
| Admin analytics | 2 admins/day | 1 (medium) | 60% | 2 person-months | **6** |
| Patient satisfaction survey | 350/day | 0.5 (low) | 80% | 0.5 person-months | **280** |

**Conclusion from this RICE analysis:**
SMS reminders score highest because they affect the most users, we're confident in the impact, and the effort is low. This becomes v1 priority #1. USSD check-in and patient satisfaction survey are tied — but USSD check-in is the core product mechanism, so it's prioritised on strategic grounds (RICE is a guide, not a mandate).

---

## Common RICE Mistakes

1. **Inflating confidence** — If you haven't talked to users, your confidence should be 50%, not 90%
2. **Ignoring strategic importance** — A low RICE score doesn't mean a feature is unimportant if it's core to the product vision
3. **Using it in isolation** — Combine with stakeholder input and strategic context
4. **Not revisiting scores** — RICE scores should change as you learn more

---

## PM Lesson

> RICE is a conversation starter, not a decision machine. Its real value is making your assumptions explicit so your team can debate them — not producing a score that ends the debate.
