# Changelog

The public release history of `@suzume-design/color` starts at `1.0.0`.
Releases of the upstream package this code was derived from are **not** listed
- see [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) for provenance.

## [1.0.0] - 2026-10-04

First Suzume Design release.

### Added

- `generate(color, options)` - light/dark palette generation (`index`,
  `list`, `format`).
- `getRgbStr(color)` - RGB channel string for CSS `rgb(var(--token))`.
- `getPresetColors()` - all presets with `light` / `dark` / `primary`.

### Changed

- Package name: `@arco-design/color` -> `@suzume-design/color`.
- Primary palette preset: `arcoblue` -> `suzumeblue`.
- Version baseline reset to `1.0.0`.
- Added `exports` map and explicit `files` list.
