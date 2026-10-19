---
name: security-questionnaire-first-pass
description: "FDE security workflow: Security questionnaire first pass. Use when a forward deployed or solutions engineer asks for help with security questionnaire first pass."
---

# Security questionnaire first pass

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Gather your approved security docs (SOC 2 summary, DPA, architecture).
2. Prompt the AI to answer only from those docs and mark gaps NEEDS REVIEW.
3. Route NEEDS REVIEW items to security/legal owners.
4. Store final answers in your RFP tool (e.g. Loopio, Responsive) for reuse.
5. Track turnaround time per questionnaire.

## Prompts

### Data and security questionnaire prep

The customer sent this security/IT questionnaire: [PASTE]. Using our documentation [PASTE], draft answers. Mark any question where our docs don't clearly support an answer as NEEDS REVIEW instead of guessing.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
