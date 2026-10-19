---
name: discovery-to-brief-in-15-minutes
description: "Use after a customer discovery call to turn raw call notes or a transcript into a deal summary, a 5-bullet AE brief and a follow-up email draft. Triggers: \"summarize this discovery call\", \"write the AE brief\", \"draft the follow-up from my call notes\"."
---

# Discovery-to-brief in 15 minutes

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Get the customer's consent before recording, then record with a notetaker your company has approved (e.g. Fathom, Granola). If there is no recording, use your typed notes.
2. Paste the transcript into your AI tool with the 'deal summary' prompt.
3. Ask it to list every assumption not stated by the customer.
4. Fix gaps with the user, then generate a 5-bullet brief for the AE and a follow-up email draft (use the second prompt). Do not send the email.
5. The user logs the brief in CRM and sets next-step dates.

## Prompts

### Turn call notes into a deal summary

Here are raw notes from a discovery call: [PASTE]. Rewrite them as: current state, desired outcome, metrics they care about, decision process, technical environment, risks, and open questions. Flag anything I assumed but they did not say.

### AE brief and follow-up email

From this corrected deal summary [PASTE], write (1) a 5-bullet brief for my account executive: pain, deadline, must-haves, buying path, next step with date, and (2) a short follow-up email to the customer recapping what we heard and the agreed next steps. Use only facts in the summary.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
