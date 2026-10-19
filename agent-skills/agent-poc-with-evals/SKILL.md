---
name: agent-poc-with-evals
description: "FDE POC workflow: Agent POC with evals. Use when a forward deployed or solutions engineer asks for help with agent POC with evals."
---

# Agent POC with evals

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Pick one narrow task and collect 20–50 real example inputs (with permission).
2. Build the first version with an agent framework (e.g. LangGraph, OpenAI Agents SDK).
3. Write expected outputs and run them through an eval tool (e.g. promptfoo, DeepEval).
4. Trace failures with an observability tool (e.g. Langfuse, LangSmith).
5. Report pass rate against the agreed criteria, not vibes.

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
