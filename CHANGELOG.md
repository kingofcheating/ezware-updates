# Changelog

## [1.0.8] - 2026-07-17

### Changed

- Replaced custom monitor-rate detection and manual frame sleeping with standard DirectX VSync presentation.
- Diagnostics now show the measured render rate instead of an artificial automatic FPS target.

### Performance

- Removed the process-wide one-millisecond Windows timer-resolution request.
- Removed custom frame-scheduling state and redundant monitor refresh-rate polling.
- Prevented an uncapped busy loop while allowing DirectX to pace frames to the active display.

## [1.0.7] - 2026-07-17

### Fixed

- Validated runtime offsets only after the running Roblox client version is known.
- Removed undefined unaligned pointer reads from child-list traversal.
- Shut down cleanly when DirectX presentation fails instead of repeatedly rendering into a failed swap chain.

### Performance

- Moved remote player and entity memory reads outside the shared render/scanner mutex.
- Reused the process write handle instead of reopening it for every memory write.
- Replaced quadratic entity duplicate checks with hash-based lookups.
- Reduced contention between entity cleanup, cache refreshes, and frame rendering.

## [1.0.6] - 2026-07-17

### Fixed

- Fixed the crash that could occur when saving or updating a profile.
- Reworked profile, autoload, and compatibility-file I/O with bounded native file operations.
- Rejected incomplete updater and offset responses instead of accepting truncated downloads.
- Fixed long-session timers that could wrap after roughly 49 days of Windows uptime.
- Added reliable cleanup for process handles, overlay state, and partially initialized UI backends.
- Corrected the version shown at startup and in the executable's Windows properties.

### Changed

- Removed the unused integration tab and kept navigation focused on the six working pages.
- Tightened update-version validation and DirectX render-target recovery.
- Limited the supported build target to Windows x64.

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

