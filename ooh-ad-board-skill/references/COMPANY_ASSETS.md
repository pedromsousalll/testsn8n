# Company Assets: What to request and how to use it (generic/off-brand)

## Goal
This document defines how the agent should handle company/brand assets without making anything up.

## 1) Do not invent brand assets
If the user doesn’t provide assets, do not fabricate:
- logos
- exact colors
- fonts
- legal disclaimers

Instead, request them or use neutral placeholders.

## 2) Assets to request (checklist)
Ask for any of the following that applies:

### Brand kit
- Logo files: SVG preferred + PNG fallback
- Color palette: HEX values + primary/secondary usage rules
- Fonts: heading + body, with weights
- Tone of voice guidelines

### Product assets
- Product photos / renders
- Screenshots (desktop + mobile)
- Key features list (approved wording)
- Offer details + terms

### Proof assets (marketing decks)
- Case studies, testimonials, press quotes
- Metrics with source and timeframe
- Customer logos (permissioned)

### Media assets (OOH/ad boards)
- Required board sizes and safe areas
- Media owner specs (PDF)
- QR destination URL + tracking rules

## 3) Placeholder defaults (when missing)
If required info is missing, use placeholders explicitly:
- Colors: `Primary: #000000`, `Accent: #0052CC` (placeholder)
- Fonts: `Heading: Inter Bold`, `Body: Inter Regular` (placeholder)
- Legal line: `*Terms apply. See website for details.*` (placeholder)

Label as "PLACEHOLDER" so it’s clear it must be replaced.

## 4) Usage rules
- Keep logos in safe area; avoid stretching
- Ensure contrast meets accessibility (WCAG AA when applicable)
- Use consistent naming and versioning for exported files

## 5) Output-ready asset list
When finishing a deliverable, repeat a short list of needed files:
- `logo.svg`, `logo.png`
- `colors.txt` (HEX)
- `fonts.txt`
- `product_images/`
- `claims_and_sources.md`
