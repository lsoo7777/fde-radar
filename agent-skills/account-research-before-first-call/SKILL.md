---
name: account-research-before-first-call
description: "Use before a first call with a new prospect to turn the company's public info (site, 10-K, press releases, attendee titles) into a one-page call plan: likely pains as hypotheses, 10 ranked discovery questions and 3 not-a-fit signals. Triggers: \"prep me for my first call with X\", \"research this account\"."
---

# Account research before first call

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Ask the user to paste the company's public info (site pages, latest 10-K or press releases) and the attendees' titles. If you have web access, you may read public pages yourself; cite the URL for every fact. Do not scrape LinkedIn.
2. Summarize business model, recent changes and likely priorities. Label every inferred pain or priority HYPOTHESIS.
3. Generate 10 discovery questions ranked by importance.
4. Flag 3 'not a fit' signals to watch for.
5. Return a one-page call plan with these sections: business model, recent changes, likely pains (hypotheses), 10 ranked questions, 3 not-a-fit signals, open questions.

## Prompts

### Discovery call prep

I have a discovery call with [COMPANY], a [INDUSTRY] company, with [ROLE OF ATTENDEES]. Our product does [ONE-LINE PRODUCT]. Using only public info I paste below, list: 5 likely business pains, 10 open-ended discovery questions ranked by importance, and 3 signals that this is NOT a fit. Info: [PASTE]

### Map the stakeholders

From this email thread and call notes [PASTE], build a stakeholder map: name, title, what they care about, likely objection, influence (high/med/low). Suggest one question to ask each person next.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
