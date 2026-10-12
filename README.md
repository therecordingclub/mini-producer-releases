# Mini Producer releases

This repository holds the public, versioned release files for Mini Producer on macOS.

## Current preview

[Mini Producer 2026.10.12-2](https://github.com/therecordingclub/mini-producer-releases/releases/tag/v2026.10.12-2) is an unsigned, unnotarized preview for Apple silicon Macs running macOS 26.2 or later. The app uses an ad hoc signature, and Gatekeeper may block the installer.

The preview requires a licensed Ableton Live 12 installation and an OpenAI account. Musical listening also requires an OpenAI API key with available credit, or it can be skipped with musical results left unapproved. Optional Splice and Suno features use the recipient's own accounts.

A fresh recipient Mac has not completed the full installation, permissions, account, and Keychain flow. The included CC0 starter drum kit passed technical checks but has not received musical listening approval.

## Verify downloads

Each release includes `SHA256SUMS`. After downloading all three files into one directory, run:

```sh
shasum -a 256 -c SHA256SUMS
```

Product requirements and measured checks are published at [mini-producer-macos.pages.dev](https://mini-producer-macos.pages.dev/).
