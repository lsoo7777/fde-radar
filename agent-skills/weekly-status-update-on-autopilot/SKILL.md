---
name: weekly-status-update-on-autopilot
description: "FDE stakeholders workflow: Weekly status update on autopilot. Use when a forward deployed or solutions engineer asks for help with weekly status update on autopilot."
---

# Weekly status update on autopilot

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Keep a running notes doc per customer during the week.
2. Friday: paste notes into the status prompt (RAG status, done, next, blockers).
3. Check every owner and date is real.
4. Send it and pin it in the shared channel.
5. Escalate any red item with the escalation prompt the same day.

## Prompts

### Weekly customer status update

Write a weekly status email for [CUSTOMER] from these notes [PASTE]: green/yellow/red status, done this week, next week, blockers needing their action (with owner and date), decisions needed. Under 200 words.

### Escalation email

Draft a calm escalation email to [CUSTOMER EXEC] about [ISSUE]: what happened, impact, what we've done, what we need from them, and the date of the next update. No blame, no hedging.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
