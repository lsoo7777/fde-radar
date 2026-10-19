---
name: tailored-demo-in-an-hour
description: "FDE demo prep workflow: Tailored demo in an hour. Use when a forward deployed or solutions engineer asks for help with tailored demo in an hour."
---

# Tailored demo in an hour

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. List the top 3 pains from discovery.
2. Prompt the demo-story template to map pain → feature → outcome.
3. Generate fake but realistic demo data as CSV and load it into your sandbox.
4. Run the 'pre-mortem my demo' prompt as the skeptical buyer.
5. Record a 3-minute Loom of the flow for async stakeholders.

## Prompts

### Build a tailored demo story

Our product features: [LIST]. Prospect pains from discovery: [LIST]. Build a 20-minute demo flow: opening hook tied to their top pain, 3 scenes (pain → feature → outcome), and a close asking for a specific next step. Cut any feature that doesn't map to a pain.

### Generate realistic demo data

Generate 25 rows of realistic but fake sample data for a [INDUSTRY] demo of [USE CASE] as CSV with columns [COLUMNS]. Include 3 edge cases that would make the demo more convincing. No real company or person names.

### Pre-mortem my demo

Here is my demo outline: [PASTE]. Act as a skeptical [BUYER ROLE]. List the 7 moments where you would lose interest or push back, and how I should fix each.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
