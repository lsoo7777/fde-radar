---
name: integration-debugging-loop
description: "Use when a customer integration is failing (API errors, webhooks, auth, timeouts): triages pasted logs and request/response pairs into 3 ranked root causes with the next diagnostic step for each, then writes a runbook entry and a plain-English customer summary. Triggers: \"debug this integration\", \"why is this API call failing\", \"triage these logs\"."
---

# Integration debugging loop

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Reproduce the issue and capture logs, request/response and environment. Redact tokens, API keys, passwords and personal data before pasting anything into an AI tool.
2. Paste logs into the triage prompt for ranked root causes.
3. The user tests the top hypothesis with Postman, curl or a small script, and pastes the result back.
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
