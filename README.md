# filepress-releases

Public **installers**, **auto-update artifacts**, and the **download site** for [FilePress](https://github.com/achuthhadnoor/filepress-desktop).

This repository intentionally contains **no application source**. Builds are published here from FilePress CI on version tags (`v*`).

## Download

**Website:** https://achuthhadnoor.github.io/filepress-releases/

Or grab installers from [Releases](https://github.com/achuthhadnoor/filepress-releases/releases/latest).

| Platform | Asset |
|---|---|
| macOS Apple Silicon | `FilePress_*_aarch64.dmg` |
| macOS Intel | `FilePress_*_x64.dmg` |
| Windows | `FilePress_*_x64-setup.exe` (NSIS) |

macOS builds may be unsigned — use Right-click → Open the first time if Gatekeeper warns.

## Auto-updates

Installed apps check:

`https://github.com/achuthhadnoor/filepress-releases/releases/latest/download/latest.json`

Source, issues, and development live in [achuthhadnoor/filepress-desktop](https://github.com/achuthhadnoor/filepress-desktop).
