# Changelog

## 2026-04-06

- **11:45 UTC** — Created project at `Documents/github/tbt` with Astro and Tailwind; set agent workspace root to this folder; added landing page (“Tam Builds Things”) with black uppercase text on a neon pink background.
- **13:27 UTC** — Neo-brutalist index layout: header with headshot, about copy, and sections Now / Previously / Contact (example links); Google Fonts Faculty Glyphic (headers) and Funnel Sans (body); headshot copied to `public/headshot.png`.
- **14:05 UTC** — Contact section matches Previously (white panel, black rules); link cards use subtle pink hover (`#fbcfe8`); optional `explainer` field on `SiteLink` with sample copy on a few rows.
- **15:00 UTC** — Added dashed “Rollover test” section with six white swatch links (four pink-toned, two alternate) and named labels plus hex sublines; refactored link button classes into `linkButtonShell` + hover.
- **15:10 UTC** — Link hover uses Tailwind `pink-100` (Soft Blush); Contact section uses dashed outer border like the rollover test block; rollover swatch data uses `code` field (Soft Blush shows “Tailwind pink-100”).
- **15:55 UTC** — Removed the “Rollover test” section and its `RolloverSwatch` data.
- **16:10 UTC** — Headshot easter egg: googly eyes appear on hover (CSS); pupils follow the cursor within each eye via a small rAF-throttled script active only while hovering; `prefers-reduced-motion` disables it; `will-change` on pupils only during tracking.
- **16:45 UTC** — Contact: `grid grid-cols-2` (half-width cells), labels only (no URL line); `linkButtonContact` variant; fixed stray comma in `nowLinks` array.
- **17:05 UTC** — Replaced `public/favicon.svg` with a symmetric black “T” on cream `#fffef2` (vector paths, no font dependency). `favicon.ico` unchanged — regenerate locally if you need a matching `.ico`.
