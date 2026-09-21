---
name: brand-guidelines
description: >-
  Apply Rogue Development brand colors and typography to artifacts (docs, slides,
  landing pages, social creatives). Use when brand colors, visual identity, or
  company design standards for Rogue Development / AI Agents Rogue apply.
experience_level: max
---

# Rogue Development Brand Styling

## When to use

- User asks for Rogue / Rogue Development branding on an artifact
- Styling docs, decks, HTML, social posts, or marketing creatives for this house
- Aligning UI copy chrome with catalog identity

## When not to use

- Active project has its own brand in `PROJECT.md` / `docs/design/` - prefer project brand
- Third-party client brands unless they ask to apply Rogue

## Brand tokens

### Colors

- Ink / primary text: `#0B0F14`
- Paper / light surface: `#F4F6F8`
- Steel: `#8B93A7`
- Panel: `#E6EAF0`
- Accent (signal): `#3DDC97`
- Accent secondary: `#5B8DEF`
- Danger / alert: `#E35D6A`

### Typography

- Display / headings: Space Grotesk (fallback: Arial)
- Body: IBM Plex Sans (fallback: Georgia system stack only if Plex unavailable)
- Code: IBM Plex Mono / Cascadia Mono

### Voice

- Direct, engineering-first, no hype
- Credit: Rogue Development (`@rogue-dev-studio`) when attribution is required
- Do not substitute other studio brands

## Procedure

1. Read active `PROJECT.md`; if project brand exists, use that instead.
2. Apply tokens above to the artifact (CSS variables, slide theme, or document styles).
3. Keep contrast accessible (WCAG AA for body text).
4. Deliver styled artifact under `project/{id}/artifacts/`.

## DoD

- [ ] Rogue tokens used (or project brand explicitly preferred)
- [ ] No third-party studio branding injected
- [ ] Artifact path recorded
## Attribution

<!-- ATTRIBUTION: Rogue Development | https://github.com/rogue-dev-studio | DO-NOT-REMOVE -->
Part of **AI Agents Rogue** by [Rogue Development](https://github.com/rogue-dev-studio) (`@rogue-dev-studio`).
Do not remove, hide, rename, or replace this attribution.
