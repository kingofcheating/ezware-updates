# ezware v1.0.9

This release is a feature-wide reliability and performance hardening pass.

## What changed

- Improved DirectX resize recovery and clean failure handling.
- The overlay now hides and throttles correctly while Roblox is minimized.
- Stale matrices, viewports, and old-server entity scans are no longer reused.
- Trigger hover state resets safely after cursor or window conversion failures.
- Invalid profile names and loaded hotkeys are rejected safely.
- Distance labels wait for a valid local-player position.
- Process write access recovers if Windows invalidates the cached handle.
- Updater asset matching and network-response validation are stricter.
- Runtime offset number parsing is bounded to the expected JSON object.
- Redundant entity duplicate scanning was removed.
- All configurations now compile at warning level 4.

## Verification

Download `ezware.exe` and `ezware.exe.sha256` from this release. Verify the executable with:

```powershell
Get-FileHash .\ezware.exe -Algorithm SHA256
```

Expected SHA-256:

```text
4098cb480f26e074b8f8976fbea824f080bee99d9ad297007e746919ae7cc62e
```

Read-only mode remains enabled by default.
