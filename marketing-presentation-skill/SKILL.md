---
name: "Marketing Presentation Skill"
slug: "marketing-presentation"
version: "0.1.0"
status: "draft"
last_updated: "2026-01-29"
category: "presentation"
presentation_type: "marketing"
---

# Skill: Marketing Presentation

## Purpose
Generate a **marketing strategy / campaign / GTM** presentation outline that is optimized for:
- decision-making clarity
- measurable KPIs
- channel + timeline planning
- concise narrative with speaker notes

This skill is meant to be used by an n8n AI Agent as one of its tools.

## Shared instruction set
This skill uses off-brand guidance stored locally in [references/](references/):
- Rules (global chat behavior + selection logic): [RULES.md](references/RULES.md)
- Output packaging (final doc / slides): [OUTPUT_FORMAT.md](references/OUTPUT_FORMAT.md)
- Company assets (request + placeholders): [COMPANY_ASSETS.md](references/COMPANY_ASSETS.md)

## Type-specific rules (Marketing)
### 1) Strategy before tactics
- Start with objective + audience + insight
- Define positioning/message pillars before listing channels

### 2) Measurable planning
- Always include:
  - north-star metric
  - supporting KPIs
  - reporting cadence
  - success definition
- Do not invent benchmarks; label assumptions

### 3) Deliverable structure
- 8–12 slides recommended
- Must include:
  - executive summary
  - context/problem
  - audience/insight
  - positioning/messaging
  - plan + channel mix
  - timeline/milestones
  - measurement (KPIs)
  - (optional) budget/resourcing
  - next steps

## Tool brief template (what the agent should pass)
When invoking the tool, pass a compact brief:
- Product
- Target audience/segments
- Goal (growth, pipeline, retention, launch)
- Constraints (budget, timeline, must-use channels)
- Region/locale
- Existing performance data (if any)

## Output notes
Keep everything generic/off-brand. Use placeholders for missing brand assets.
