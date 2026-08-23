# Changelog

## [1.0.0] — Master build — 2026-08

### Added
- LoneWare master build (modular single-file hub)
- Core: Logger, SafeCall, ConnectionManager, Config, References, HubState, Unload
- Main: Infinite Jump, No Fog, Full Bright, Remove Jitter, Network Diagnostics (read-only), ESP, Debug Mode
- Parry: Auto Parry, Auto Dash, Ball Tracker + sliders
- FFlag: JSON editor, validation, Apply (store only), Rejoin, Clear/Reset, presets, import/export
- Themes: Lavender, Purple, Violet, White, Black

### Notes
- Full source: commit `src/LoneWare.lua` from workspace `artifacts/LoneWare.lua` (~64 KB)
- Network Diagnostics replaces experimental RakNet desync (no packet manipulation)
- FFlag Apply does not call setfflag
- WindUI loaded at runtime from Footagesus releases
