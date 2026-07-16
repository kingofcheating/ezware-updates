# ezware Updates

Official release channel for ezware, including stable downloads, update history, and compatibility improvements.

[Download the newest stable release](https://github.com/kingofcheating/ezware-updates/releases/latest)

## Why use the latest release?

The newest build delivers a cleaner startup experience, more reliable updates, durable configuration storage, and smoother rendering across a wide range of computers.

## Highlights

- **Clear startup experience** — balanced layout, readable status text, polished transitions, and controls designed to avoid clipping or overlap.
- **Rendering-rate selector** — choose 60, 144, 165, 240, 360 FPS, or Unlimited. This controls rendering throughout the desktop overlay.
- **Responsive performance** — frame pacing is tuned for high-refresh-rate displays while avoiding unnecessary CPU and GPU load.
- **Automatic update checks** — startup checks GitHub for a newer stable version and reports the installed and latest versions clearly.
- **Direct release access** — the startup screen includes a button that opens the newest release page.
- **Useful update feedback** — connection, version-check, download, validation, and restart results are shown clearly.
- **Durable configuration profiles** — save, load, update, and choose an automatic startup profile.
- **Protected config storage** — profiles are kept under the user's local application-data folder instead of temporary storage, so clearing temporary files does not remove them.
- **Atomic saves and recovery** — backup and recovery handling reduces the chance of losing a profile if a save is interrupted.
- **Older-config migration** — compatible legacy profiles are detected and migrated into the current storage location.
- **Config compatibility** — the loader supports current and older supported profile formats.
- **Customizable overlay UI** — adjustable menu appearance, on-screen feedback, colors, crosshair, FPS display, and visual previews.
- **Standalone external architecture** — runs as a separate Windows desktop application and does not inject a DLL into Roblox.
- **Compatibility-focused startup** — clear Roblox connection status, retry handling, font fallback, and automatic overlay alignment.
- **Stable cleanup** — overlay and graphics resources are released cleanly when the application exits.

## Updating

1. Open the [latest release](https://github.com/kingofcheating/ezware-updates/releases/latest).
2. Download `ezware.exe`.
3. Replace the older executable and launch the new version.

The built-in checker will also notify you when a newer stable release is available.

## Configuration location

Current profiles are stored in:

`%LocalAppData%\ezware\Vault`

Do not store profiles beside temporary downloads if you want them to remain available long term.

## Current stable version

**v1.0.2 — Stable External Update**

See the [v1.0.2 release notes](https://github.com/kingofcheating/ezware-updates/releases/tag/v1.0.2) for the complete change history.

> Use software responsibly and follow the rules and terms that apply to the software and services you use.
