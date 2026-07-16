<h1 align="center">ezware ezware</h1>

<p align="center"><strong>Official downloads - release notes - verified updates</strong></p>

<p align="center">
  <a href="https://github.com/kingofcheating/ezware-updates/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/kingofcheating/ezware-updates?style=for-the-badge&color=7c6cff&label=LATEST"></a>
  <a href="https://github.com/kingofcheating/ezware-updates/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/kingofcheating/ezware-updates/total?style=for-the-badge&color=7c6cff"></a>
  <a href="https://discord.gg/xAQ8WJVHe9"><img alt="Discord" src="https://img.shields.io/badge/Discord-join-7c6cff?style=for-the-badge&logo=discord&logoColor=white"></a>
  <img alt="Windows x64" src="https://img.shields.io/badge/Windows-x64-7c6cff?style=for-the-badge&logo=windows11&logoColor=white">
</p>

<p align="center">
  A standalone Windows application with a streamlined interface,<br>
  durable profiles, automatic frame pacing, and verified updates.
</p>

<p align="center">
  <a href="https://github.com/kingofcheating/ezware-updates/releases/latest"><strong>Download latest release</strong></a>
  - <a href="#getting-started">Getting started</a>
  - <a href="#security--verification">Security</a>
  - <a href="CHANGELOG.md">Changelog</a>
  - <a href="https://discord.gg/xAQ8WJVHe9">Discord</a>
</p>

> [!IMPORTANT]
> **Educational and authorized testing only.** Do not use ezware in live or public games. Follow Roblox's Terms of Use and the rules of every experience or service you use.

## At a glance

| Interface | Reliability | Updates |
| :--- | :--- | :--- |
| Six focused sections | Durable profiles with recovery backups | Automatic version checks |
| Unified Visuals workspace | Read-only safety mode by default | SHA-256 validation |
| Smooth, consistent animations | Automatic display-aware pacing | Clear installed/latest status |

## Features

<details open>
<summary><strong>Interface and visuals</strong></summary>

- Home, Aim, Visuals, Movement, Profiles, and Settings navigation
- Configurable player overlay, crosshair, hit feedback, FPS display, colors, and previews
- Smooth opening, closing, tab, control, tooltip, and notification animations
- DPI-aware scaling, opacity, privacy mode, watermark, and notification controls

</details>

<details>
<summary><strong>Profiles and safety</strong></summary>

- Save, load, update, delete, and automatically load profiles
- Unsaved-change protection, recovery backups, and legacy profile migration
- Read-only mode blocks input automation and process-memory writes while visuals remain available
- Clear connection, safety, active-profile, and diagnostics status

</details>

<details>
<summary><strong>Performance and updates</strong></summary>

- Automatic frame pacing follows the active display between 60 and 240 FPS
- Avoids redundant overlay repositioning when the game window has not changed
- Built-in update checker with GitHub release downloads and SHA-256 verification
- Runs as a separate Windows application without DLL injection

</details>

## Getting started

1. Open the [latest release](https://github.com/kingofcheating/ezware-updates/releases/latest).
2. Read the release notes and expand **Assets**.
3. Download **`ezware.exe`** and **`ezware.exe.sha256`**.
4. Verify the executable against the published checksum.
5. Launch the application. Performance is configured automatically.

> [!TIP]
> ezware checks for new releases on startup. To update manually, replace the old executable with the newer verified file.

## Controls

| Key | Action |
| :--- | :--- |
| `Insert` | Show or hide the menu |
| `F10` | Toggle privacy mode |
| `End` | Request a safe exit |

## Profile location

```text
%LocalAppData%\ezware\Vault
```

Profiles are stored outside temporary directories. Compatible profiles from the older location are migrated automatically when possible.

## Security & verification

ezware can open the Roblox process, read and write memory, send mouse input, connect to GitHub for updates, and replace its executable during an update. Security tools may scrutinize those behaviors, especially because the application is not digitally signed.

Before running a download:

- Use only the [official releases page](https://github.com/kingofcheating/ezware-updates/releases).
- Download the checksum beside the executable.
- Review security warnings instead of dismissing them automatically.
- Do not trust mirrors, reuploads, or files shared through direct messages.

### Latest reviewed build

| Version | SHA-256 | Code signing |
| :--- | :--- | :--- |
| **v1.0.5** | `749d22df28883726025495b1baa777a2e3df4f77baa162bef312f986fec06d32` | Not digitally signed |

This value applies only to the official file with that exact hash. It is not a guarantee for modified or reuploaded copies.

See [SECURITY.md](SECURITY.md) for vulnerability reporting guidance.

---

<p align="center"><sub>ezware ezware - Windows x64 - official releases only</sub></p>

