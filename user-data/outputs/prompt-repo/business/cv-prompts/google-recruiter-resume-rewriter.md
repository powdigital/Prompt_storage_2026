# The 6-Second CV Rewriter (UK Design & UX)

## What it does
Rewrites your entire CV to pass the brutal 6-second recruiter scan — calibrated for UK hiring norms and the specific language of product design, UX, service design, and design leadership roles. Outputs a complete ready-to-submit CV plus a tracked-changes summary of improvements.

## Best model
Claude Sonnet, GPT-4o

## Prompt
```
You are a senior design recruiter at a UK tech or consultancy firm — you've reviewed 100,000+ CVs for product design, UX, service design, and design leadership roles. You decide within 6 seconds whether a candidate progresses, because that's all the time a CV gets before the next one loads.

I need my entire CV rewritten to survive those 6 seconds.

Context about me:
- Based in the UK — use British English throughout (CV not resume, programme not program, organisation not organization, colour not color)
- Discipline: product design / UX / service design
- Target roles may sit inside in-house product teams, consultancies, or agencies

Rewrite the following:

**Professional summary**
A 2–3 sentence power statement communicating who I am, my design discipline, and my impact. Should reference the type of problems I solve (not just job titles held). Avoid generic phrases like "passionate designer" or "strong communicator."

**Every bullet point**
Rewrite using outcome-first structure: what changed, for whom, and how. Example: "Redesigned the onboarding flow, reducing drop-off by 34% across 2M users by introducing progressive disclosure and contextual tooltips." Avoid feature-delivery language ("designed X screen") — focus on business and user outcomes.

**Metrics and evidence**
Add specific numbers wherever possible: conversion rates, NPS uplift, time-on-task reduction, cost savings, team size led, delivery timelines, research participants, DAU/MAU impact. If metrics aren't known, use scale indicators (e.g. "enterprise platform serving 40,000 users").

**Weak language elimination**
Replace: "helped," "assisted," "involved in," "contributed to," "worked on," "was responsible for"
With: "led," "defined," "shipped," "reduced," "increased," "facilitated," "prototyped," "validated," "drove adoption of"

**Design-specific skills section**
Organise into: Research Methods | Design Tools | Prototyping & Testing | Systems & Ops | Collaboration & Delivery
Match terminology to the target job description provided.

**Length and hierarchy**
Two pages maximum for 10+ years experience, one page otherwise. Name largest. Section headers clear. Body text scannable. Cut anything older than 10 years unless landmark.

**UK CV conventions**
No photo, no date of birth, no nationality. Personal statement at the top, not a cover letter. LinkedIn URL included. References line: "Available on request."

**Red flag removal**
Smooth over employment gaps with date formatting (years only where helpful), remove outdated tools (e.g. Flash, Dreamweaver, Axure if not relevant), cut anything that dates or weakens the narrative.

**Before/after comparison**
Show the 3 weakest original bullets alongside their rewrites, with a one-line explanation of what was wrong.

Format the output as:
1. Complete rewritten CV, ready to copy
2. Tracked-changes summary — what was cut, rewritten, or restructured and why

My current CV and target job description:
[PASTE YOUR FULL CV AND THE JOB DESCRIPTION HERE]
```

## Example output
*Add a sample output here once you've tested it.*

## Tags
`cv` `job-hunting` `ux` `product-design` `service-design` `uk` `recruiter` `rewriting` `career`
