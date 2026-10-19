---
name: deal-debrief-to-product-feedback
description: "Use after a deal is won or lost to turn notes into an internal debrief (why we won/lost, what they valued, lessons) and a product-gap list with verbatim customer quotes grouped by theme and deal size. Triggers: \"deal debrief\", \"win/loss notes\", \"product feedback from this deal\"."
---

# Deal debrief → product feedback

Run this workflow with the user step by step. Ask for any missing input before starting, use only facts the user provides, and mark anything you had to assume as ASSUMPTION.

## Steps
1. After win/loss, paste notes into the debrief prompt.
2. Extract product gaps. Use only verbatim quotes that appear in the notes; if a gap has no quote, say so.
3. Group gaps by theme and deal size.
4. The user shares the gap list with product monthly in a single doc.
5. The user tracks which gaps ship and tells the customer.

## Prompts

### Internal deal debrief

Summarize this deal for my internal team from these notes [PASTE]: why we won/lost, what the customer actually valued, product gaps raised (each with a verbatim quote from the notes or "no quote", a theme, and the deal size), and 3 lessons for the next similar deal.

## Rules

- Never invent customer facts, numbers, quotes or dates.
- Don't paste customer data into an AI tool your company hasn't approved.
- Finish with a short list of open questions for the user.

From FDE Radar, https://fderadar.com
