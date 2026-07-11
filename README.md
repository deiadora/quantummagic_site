[quantummagic-ai-README.md](https://github.com/user-attachments/files/29910615/quantummagic-ai-README.md)
# quantummagic.ai

> The relational pathways API — a structured map of how constructive conversations progress, for AI systems.

## What this is

Product page for Quantum Magic, the relational pathways API. Covers the three capabilities (recognize, guide, evaluate), one arc as structure, what it is not, why an API and not a prompt, use contexts, and the two access paths (API and individual companion).

## Stack

Single-file static site — one `index.html`, no build step, no frameworks, no dependencies beyond Google Fonts.

Shared deiadora ecosystem design system:
- CSS custom properties; Cormorant Garamond / Exo 2 / DM Sans
- Three themes (default, dark, light) with system-preference tracking, persisted via `localStorage`
- A/A text-size toggle (115% scaling), persisted via `localStorage`
- WCAG AA contrast verified for all text/background pairs in all three themes
- Skip link, semantic sections, `prefers-reduced-motion` support

## Deploy

Cloudflare Pages. No build command; root directory as output. Replace placeholder links (mail subjects, audio files, or invite URLs) noted in HTML comments where present.

## Ecosystem

Part of the deiadora ecosystem — ten sites, one design system, one author. Front door: [deiadora.com](https://deiadora.com).

© Deiadora Blanche. All rights reserved.
