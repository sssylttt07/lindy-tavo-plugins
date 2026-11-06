# Changelog

## Lin Memory Manager 1.5.0 & Lin World Archive 1.2.0 — 2026-11-06

Updated releases of the two memory plugins; replaces 记忆管家 1.2.2 and 世界档案 1.1.8.

- `Lin记忆管家 V1.5.0.tpg` — Memory Manager, `manifest.json` version: 1.5.0 (package id `lin.memory-keeper`).
- `Lin世界档案 V1.2.0.tpg` — World Archive, `manifest.json` version: 1.2.0 (package id `lin.world-archive`).

### Verified

- All bundled `.js` files pass `node --check` (2 per package).
- `manifest.json` and `locales/*.json` parse cleanly (3 per package).

## Lindy 1.1.6 — 2026-11-05

Regex manager for status panels, value bars, and collapsible sections. Saves tokens vs. raw CSS output when paired with a Lin theme.

- Status panels, value bars, and collapsible sections are managed as presets and exported as beautification regex.
- Legacy configurations that contain unknown entries are ignored on load, so older setups load cleanly without any manual cleanup.
- `manifest.json` version: 1.1.6.

### Verified

- Plugin files (`entry.js`, `ui/app.js`, `ui/core.js`) pass `node --check`.
- `manifest.json` and `locales/*.json` parse cleanly.
