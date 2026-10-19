---
name: integration-debugging-loop
description: "FDE implementation workflow: Integration debugging loop. Use when a forward deployed or solutions engineer asks for help with integration debugging loop."
---

# Integration debugging loop

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Reproduce the issue and capture logs, request/response and environment.
2. Paste logs into the triage prompt for ranked root causes.
3. Test the top hypothesis with Postman or a small script.
4. Document the fix as a runbook entry.
5. Share a plain-English summary with the customer.

## Prompts

### Debug log triage

Here is an error log from a customer environment: [PASTE]. Summarize what likely failed, the 3 most probable root causes in order, and the exact next diagnostic step for each. Say clearly if the log is insufficient.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
