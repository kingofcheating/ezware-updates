# ezware v1.0.8

This release simplifies frame pacing so the overlay follows the display through standard DirectX VSync.

## What changed

- Replaced custom monitor refresh-rate detection with standard VSync presentation.
- Removed manual frame sleeping and custom scheduling state.
- Removed the process-wide one-millisecond timer-resolution request.
- Diagnostics now report the actual measured render rate.
- Retained clean shutdown handling for DirectX presentation failures.

## Verification

Download `ezware.exe` and `ezware.exe.sha256` from this release. Verify the executable with:

```powershell
Get-FileHash .\ezware.exe -Algorithm SHA256
```

Expected SHA-256:

```text
4ee20c5fc6f853ccf2f05055da710e0996363c8dcb89e039f72ad48d30a348be
```

Read-only mode remains enabled by default.
