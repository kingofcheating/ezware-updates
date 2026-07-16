<h1 align="center">◆ ezware</h1>

<p align="center">
  <strong>Official downloads · release notes · verified updates</strong>
</p>

<p align="center">
  <a href="https://github.com/kingofcheating/ezware-updates/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/kingofcheating/ezware-updates?style=for-the-badge&color=7c6cff&label=LATEST"></a>
  <a href="https://github.com/kingofcheating/ezware-updates/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/kingofcheating/ezware-updates/total?style=for-the-badge&color=7c6cff"></a>
  <img alt="Windows x64" src="https://img.shields.io/badge/Windows-x64-7c6cff?style=for-the-badge&logo=windows11&logoColor=white">
</p>

<p align="center">
  A standalone Windows application with a configurable interface,<br>
  durable profiles, and built-in update verification.
</p>

<p align="center">
  <a href="https://github.com/kingofcheating/ezware-updates/releases/latest"><strong>Download latest release</strong></a>
  ·
  <a href="#getting-started">Getting started</a>
  ·
  <a href="#security--verification">Security</a>
  ·
  <a href="https://github.com/kingofcheating/ezware-updates/releases">Version history</a>
</p>

> [!IMPORTANT]
> **Educational and authorized testing only.** Do not use ezware in live or public games. Follow Roblox's Terms of Use and the rules of every experience or service you use.

## At a glance

| Experience | Reliability | Updates |
| :--- | :--- | :--- |
| Smooth, DPI-aware dark interface | Durable configs with recovery backups | Automatic version checks |
| Custom colors, crosshair, FPS, and visuals | Safer input, camera, and projection handling | SHA-256 validation before installation |
| 60–360 FPS caps or Unlimited | Legacy profile migration and support | Clear installed/latest version status |

## Features

<details open>
<summary><strong>Aim and input</strong></summary>

- Configurable Aimbot with FOV, smoothing, target part, team check, and sticky targeting
- Silent Aim with physical-click handling and rapid-click queuing
- Triggerbot with adjustable radius, delay, cooldown, and team check
- Hardened camera, projection, target selection, and input delivery

</details>

<details>
<summary><strong>Visuals and interface</strong></summary>

- Customizable player visuals, crosshair, hit feedback, FPS counter, and accent color
- Smooth animations, responsive layout, and properly scaled text
- Render-rate options for **60, 144, 165, 240, 360, or Unlimited**
- Clear connection, safety, profile, and update status

</details>

<details>
<summary><strong>Profiles and updates</strong></summary>

- Save, load, edit, and automatically load profiles
- Atomic saves, persistent recovery backups, and older-config support
- Built-in update checker with verified GitHub release downloads
- Runs as a separate Windows application without DLL injection

</details>

## Getting started

1. Open the [latest release](https://github.com/kingofcheating/ezware-updates/releases/latest).
2. Read its notes and expand **Assets**.
3. Download **`ezware.exe`** from this repository only.
4. Confirm the filename, version, and published SHA-256 value.
5. Launch the application and choose your preferred render rate.

> [!TIP]
> ezware checks for new releases on startup. To update manually, replace the old executable with the newer verified file.

## Config location

```text
%LocalAppData%\ezware\Vault
```

Profiles are kept outside temporary storage. Compatible profiles from the older location are migrated automatically when possible.

## Security & verification

ezware opens the Roblox process, reads and writes memory, sends mouse input, connects to GitHub for updates, and can replace its executable during an update. Security tools may scrutinize those behaviors, especially because the application is not digitally signed.

Before running a download:

- Use only the [official releases page](https://github.com/kingofcheating/ezware-updates/releases).
- Confirm the filename, version, and published SHA-256 value.
- Review warnings rather than dismissing them automatically.
- Do not trust mirrors, reuploads, or files shared through direct messages.

### Latest reviewed build

| Version | Microsoft Defender | Code signing |
| :--- | :--- | :--- |

| **v1.0.4** | No threats found during the release review | Not digitally signed |

```text
SHA-256  DE76A1B52F464C6639ACEF5340C24D03A59F0AF6539A6373841C0B1B9202461F
```

This result applies only to the official file with that exact hash. It is not a guarantee for modified or reuploaded copies.

---

<p align="center">
  <sub>◆ ezware · Windows x64 · official releases only</sub>
</p>
