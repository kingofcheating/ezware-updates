# ezware v1.0.7

This release focuses on smoother frame delivery and safer runtime initialization.

## What changed

- Runtime offsets are selected only after the active Roblox version is known.
- Player and entity memory reads no longer hold the shared render/scanner lock.
- Entity cleanup no longer blocks the render path during remote memory access.
- Process write handles are reused to reduce repeated Windows handle operations.
- Entity duplicate detection now uses efficient hash lookups.
- Unsafe unaligned child-pointer reads were replaced with defined memory copies.
- DirectX presentation failures now trigger a clean shutdown.

## Verification

Download `ezware.exe` and `ezware.exe.sha256` from this release. Verify the executable with:

```powershell
Get-FileHash .\ezware.exe -Algorithm SHA256
```

Expected SHA-256:

```text
956262a4201b21963cc9944f206caa51d93bd3e1242daa96a846b13817beeda2
```

Read-only mode remains enabled by default.
