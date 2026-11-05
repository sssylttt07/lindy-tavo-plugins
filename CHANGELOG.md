# Changelog

## Lindy 1.1.6 — 2026-11-05

Regex manager for status panels, value bars, and collapsible sections. Saves tokens vs. raw CSS output when paired with a Lin theme.

- Status panels, value bars, and collapsible sections are managed as presets and exported as beautification regex.
- Legacy configurations that contain unknown entries are ignored on load, so older setups load cleanly without any manual cleanup.
- `manifest.json` version: 1.1.6.

### Verified

- Plugin files (`entry.js`, `ui/app.js`, `ui/core.js`) pass `node --check`.
- `manifest.json` and `locales/*.json` parse cleanly.
