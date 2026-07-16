# Changelog

## [1.0.5] - 2026-07-16

### Changed

- Redesigned navigation around Home, Aim, Visuals, Movement, Profiles, and Settings.
- Combined player overlays, crosshair controls, and hit feedback under Visuals.
- Replaced the recurring startup splash with the Home dashboard.
- Standardized profile terminology and simplified the sidebar footer.
- Moved read-only safety controls to the top of Settings.
- Replaced manual performance presets with automatic display-aware frame pacing.
- Improved opening, closing, tab, control, tooltip, pulse, and notification animations.

### Performance

- Avoided redundant overlay repositioning when the target window has not changed.
- Automatically follows the active display refresh rate between 60 and 240 FPS.

### Fixed

- Applied configurable notification duration consistently.
- Prevented notification stacks from shifting through each other while fading.
- Prevented the closing menu from intercepting input during its exit animation.
- Clarified movement reset behavior and standardized control capitalization.

## [1.0.4]

- Previous application release.

