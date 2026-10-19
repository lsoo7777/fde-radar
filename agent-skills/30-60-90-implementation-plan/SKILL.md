---
name: 30-60-90-implementation-plan
description: "Use after a deal closes to build a 30-60-90 day customer implementation plan with milestones, dependencies, owners (TBD where unknown), a risk register and what \"live\" means at day 90. Triggers: \"implementation plan\", \"30-60-90 for this customer\", \"risk register for this rollout\"."
---

# 30-60-90 implementation plan

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Feed scope, team size and success criteria into the 30-60-90 prompt.
2. Generate a risk register and add customer-specific risks.
3. Ask the user for customer-side owners for every dependency; write TBD where none is given.
4. The user reviews the plan in the kickoff meeting and gets explicit agreement.
5. Turn milestones into weekly status-update headings.

## Prompts

### 30-60-90 implementation plan

Create a 30-60-90 day implementation plan for [CUSTOMER] deploying [PRODUCT] for [USE CASE] with [TEAM SIZE]. Include milestones, dependencies, customer-side owners, risks, and what 'live' means at day 90. Use TBD for any owner or date I haven't given you.

### Risk register

From this project plan [PASTE], build a risk register table: risk, likelihood, impact, early warning sign, mitigation, owner. Add 3 risks the plan doesn't mention but deployments like this commonly hit, labeled GENERIC.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
