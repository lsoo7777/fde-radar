---
name: 30-60-90-implementation-plan
description: "FDE implementation workflow: 30-60-90 implementation plan. Use when a forward deployed or solutions engineer asks for help with 30-60-90 implementation plan."
---

# 30-60-90 implementation plan

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Feed scope, team size and success criteria into the 30-60-90 prompt.
2. Generate a risk register and add customer-specific risks.
3. Assign customer-side owners for every dependency.
4. Review in the kickoff meeting and get explicit agreement.
5. Turn milestones into weekly status-update headings.

## Prompts

### 30-60-90 implementation plan

Create a 30-60-90 day implementation plan for [CUSTOMER] deploying [PRODUCT] for [USE CASE] with [TEAM SIZE]. Include milestones, dependencies, customer-side owners, risks, and what 'live' means at day 90.

### Risk register

From this project plan [PASTE], build a risk register table: risk, likelihood, impact, early warning sign, mitigation, owner. Add 3 risks the plan doesn't mention but deployments like this commonly hit.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
