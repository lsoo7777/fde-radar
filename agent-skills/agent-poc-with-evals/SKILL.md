---
name: agent-poc-with-evals
description: "Use when building an AI-agent proof of concept for a customer and you need evidence it works: turns 20-50 real example inputs into an eval set with expected outputs and pass/fail checks, and reports pass rate against agreed criteria. Triggers: \"evals for my agent POC\", \"test cases for this agent\", \"pass rate report\"."
---

# Agent POC with evals

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. Pick one narrow task and collect 20–50 real example inputs (with permission).
2. Build the first version with an agent framework (e.g. LangGraph, OpenAI Agents SDK).
3. Write expected outputs and pass/fail checks for each input (first prompt), then run them through an eval tool (e.g. promptfoo, now part of OpenAI and still MIT open source, or DeepEval).
4. Trace failures with an observability tool (e.g. Langfuse, now part of ClickHouse and still open source, or LangSmith).
5. Report pass rate against the agreed criteria with the second prompt, not vibes. A zero-tolerance check that fails means the POC fails, whatever the average.

## Prompts

### Build the eval set

Here is the agent's task: [TASK]. Here are real example inputs, shared with permission: [PASTE]. For each input, write the expected output and 1-3 pass/fail checks a script or reviewer can apply. Mark ambiguous inputs AMBIGUOUS instead of choosing an answer, and list them for the customer to label.

### Pass-rate report

Agreed criteria: [PASTE]. Eval results: [PASTE]. Report the pass rate for each criterion with counts (e.g. 27/30), say pass or fail against each threshold, list the failing ids, and give one concrete next fix. Use only the numbers provided.

(To agree the criteria first, use the poc-scope-that-gets-signed skill.)

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
