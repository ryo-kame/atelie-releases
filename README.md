# atelie-releases

Auto-update distribution channel for **Atelie** — a local-first project management app for macOS.

This repository contains release binaries only. Source code is hosted privately.

### 🌐 [**Download page → ryo-kame.github.io/atelie-releases**](https://ryo-kame.github.io/atelie-releases/)

A richer EN/JA landing page with the feature tour and download links lives on GitHub Pages
(source: [`index.html`](index.html)).

## Downloads

Latest release: https://github.com/ryo-kame/atelie-releases/releases/latest

Each release contains:
- `Atelie_<version>_universal.dmg` — installer for macOS (Intel + Apple Silicon)
- `Atelie.app.tar.gz` — used by the in-app updater
- `Atelie.app.tar.gz.sig` — ed25519 signature for tamper detection
- `latest.json` — updater manifest

## Verification

Updater artifacts are signed with the ed25519 public key embedded in the app
(`13AD67F331E855C4`).

https://github.com/user-attachments/assets/192a9f91-430a-494e-a144-f5e567325a43
