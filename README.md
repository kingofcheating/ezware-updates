# ezware

The official place to download ezware and see what changed.

> **Educational use only:** This project is provided for learning and authorized testing. Do not use it in live or public games. Follow Roblox's rules and the rules of any game or service you use.

**[Download the latest version](https://github.com/kingofcheating/ezware-updates/releases/latest)**

## What's included

- A clean startup screen that shows the Roblox connection and update status
- FPS options for 60, 144, 165, 240, 360, or Unlimited
- Smooth menus and animations with text that fits correctly
- Settings for the menu, colors, crosshair, FPS counter, and on-screen effects
- Configs that you can save, load, edit, and use automatically when ezware starts
- Config backups to help recover your settings if a save fails
- Support for configs made with older versions
- A configurable Aimbot with FOV, smoothness, target-part, team-check, and sticky-target controls
- Silent Aim input capture with one-shot clicks and rapid-click queuing
- Triggerbot controls for radius, team check, delay, and cooldown
- Safer camera, target-selection, projection, and input handling
- An update checker that shows your version and the newest version
- A button on the startup screen that opens the latest release
- Clear messages when an update is checked, downloaded, or fails
- Better performance on both lower-end PCs and high-refresh-rate monitors
- Runs as a separate Windows app and does not inject a DLL into Roblox

## Configs

Your configs are saved here:

`%LocalAppData%\ezware\Vault`

They are not stored in a temporary folder, so clearing temporary files will not remove them. Older configs are moved to the new folder when possible.

## How to update

1. Open the [latest release](https://github.com/kingofcheating/ezware-updates/releases/latest).
2. Download `ezware.exe`.
3. Replace your old file with the new one.

ezware also checks for updates when it starts.

## Windows Security notice

Windows Security or another antivirus may warn about or quarantine ezware. That can happen because ezware is an unsigned Windows application and uses behavior that security tools watch closely: it opens the Roblox process, reads and writes process memory, captures mouse clicks, simulates mouse input, connects over HTTPS for updates and offsets, and replaces its own executable during an update.

Those behaviors explain why a heuristic scanner may be cautious, but they do **not** prove that every warning is a false positive. Always read the exact detection instead of ignoring it automatically.

### Do I need to disable real-time protection?

We do not recommend leaving Windows real-time protection disabled or adding a broad folder exclusion. If Windows blocks the file:

1. Make sure it came from this repository's official release page.
2. Check the release version and the file's SHA-256 hash when one is provided.
3. Open **Windows Security → Virus & threat protection → Protection history** and review the exact detection.
4. Only choose **Allow on device** if you understand the warning and trust the file.

If you temporarily disable real-time protection for testing in an isolated, authorized environment, turn it back on immediately afterward. Never disable protection to run a file obtained from a reupload, direct message, link shortener, or unknown mirror.

### What the program does — and does not do

The current code was reviewed for the behaviors most people reasonably worry about:

- It does not inject a DLL or create a remote thread inside Roblox.
- It does not collect browser cookies, passwords, authentication tokens, or account credentials.
- It does not install a Windows service, scheduled task, or startup registry entry.
- Its network access is used for the GitHub update check and the runtime offset source.
- The updater validates the downloaded executable before replacing the current version.
- Settings stay in `%LocalAppData%\ezware\Vault`.

That is a description of the current design, not an unconditional safety guarantee. Only run software when you trust its source and understand what it does.

## Latest version

**v1.0.4 — Aim & Reliability Update**

Highlights include reworked Silent Aim click handling, rapid-click queuing, corrected camera rotation and address traversal, functional Trigger Radius controls, and stronger validation throughout the Aim section.

[Read the v1.0.4 update notes](https://github.com/kingofcheating/ezware-updates/releases/tag/v1.0.4)

## Important notice

This project is for educational and authorized testing purposes only. It is not intended for use in live or public games. You are responsible for following Roblox's Terms of Use and all other rules that apply.
