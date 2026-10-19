---
name: poc-scope-that-gets-signed
description: "Use when scoping a customer proof of concept: drafts a one-page POC scope (objective, 3-5 measurable success criteria, in/out of scope, data needed, weekly timeline, owners, exit decision) and pressure-tests each criterion into pass/fail tests. Triggers: \"scope a POC\", \"success criteria\", \"POC plan\"."
---

# POC scope that gets signed

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Draft the scope with the POC prompt (objective, criteria, timeline, owners).
2. Pressure-test each success criterion for measurability.
3. Review with the champion; agree on pass/fail before kickoff.
4. Turn the timeline into a shared checklist with dates.
5. Draft a recap email confirming criteria in writing for the user to review and send.

## Prompts

### Scope a proof of concept

Draft a POC scope for [COMPANY] testing [PRODUCT] for [USE CASE]. Include: objective, 3–5 measurable success criteria, in/out of scope, data and access needed from them, timeline by week, owners on both sides, and exit decision. Keep it to one page.

### Pressure-test success criteria

Here are proposed POC success criteria: [PASTE]. For each, say if it is measurable, who measures it, how it could be gamed or misread, and rewrite vague ones into concrete pass/fail tests.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
