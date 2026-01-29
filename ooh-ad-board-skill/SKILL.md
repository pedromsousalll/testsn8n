---
name: "OOH / Ad Board Presentation Skill"
slug: "ooh-ad-board-presentation"
version: "0.1.0"
status: "draft"
last_updated: "2026-01-29"
category: "presentation"
presentation_type: "ooh_ad_board"
---

# Skill: OOH / Ad Board Presentation

## Purpose
Generate an **ad-board / OOH / DOOH** presentation outline that is optimized for:
- fast readability (distance viewing)
- short-copy constraints
- placement and flighting considerations
- measurement plan

This skill is meant to be used by an n8n AI Agent as one of its tools.

## Shared instruction set
This skill uses off-brand guidance stored locally in [references/](references/):
- Rules (global chat behavior + selection logic): [RULES.md](references/RULES.md)
- Output packaging (final doc / slides): [OUTPUT_FORMAT.md](references/OUTPUT_FORMAT.md)
- Company assets (request + placeholders): [COMPANY_ASSETS.md](references/COMPANY_ASSETS.md)

## Type-specific rules (OOH)
### 1) Copy constraints
- Headline must be short, concrete, and readable in ~3 seconds
- Prefer one message per board; avoid multi-claim lists
- If a CTA is included, it must be simple (short URL / QR with a clear instruction)

### 2) Visual hierarchy
- Prioritize: Headline → Primary visual → Brand → CTA
- Keep large type sizes; maximize contrast
- Respect safe areas and avoid edge-to-edge critical text

### 3) Deliverable structure
- 6–8 slides recommended
- Must include:
  - objective + audience
  - message strategy (3-second rule)
  - concept variants (A/B/C)
  - placements/flighting
  - measurement plan
  - assets checklist + next steps

## Tool brief template (what the agent should pass)
When invoking the tool, pass a compact brief:
- Product/offer
- City/locations + placement types
- Dates/flighting
- Audience context (commute/shopping/events)
- Brand tone (if any)
- Format constraints (board sizes/specs if known)

## Output notes
Keep everything generic/off-brand. Use placeholders for missing brand assets.
