---
name: runbook-from-slack-chaos
description: "FDE implementation workflow: Runbook from Slack chaos. Use when a forward deployed or solutions engineer asks for help with runbook from Slack chaos."
---

# Runbook from Slack chaos

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Export the relevant thread(s).
2. Prompt the AI to produce a numbered runbook with checks and rollback.
3. Follow the runbook yourself once on a test environment.
4. Fix steps that fail, then publish to your wiki.
5. Link the runbook in future tickets.

## Prompts

### Runbook from tribal knowledge

Here's a messy Slack thread about how we set up [SYSTEM] for a customer: [PASTE]. Turn it into a numbered runbook with prerequisites, steps, verification checks, and rollback steps.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
