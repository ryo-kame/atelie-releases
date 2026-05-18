# atelie-releases

Auto-update distribution channel for **Atelie** — a local-first project management app for macOS.

This repository contains release binaries only. Source code is hosted privately.

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
