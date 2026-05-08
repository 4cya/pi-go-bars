# Changelog

## [0.2.1] — 2026-05-09

### Changed
- **Migrated imports** from `@mariozechner/pi-*` to `@earendil-works/pi-*` to align with the pi package namespace migration.
- Bumped peerDependencies to `@earendil-works/pi-coding-agent` and `@earendil-works/pi-tui`.

### Fixed
- **Thinking level display**: Footer now correctly shows the user's configured thinking level (e.g. "high") instead of always showing "off". The extension reads the initial level via `pi.getThinkingLevel()` on session start and re-renders on live level changes.
- **Hidden cost for opencode-go**: Per-token cost display (`$X.XXX`) is now suppressed when the active model is opencode-go (flat-rate subscription, not token-priced).

## [0.1.0] — 2026-05-01

Initial release
