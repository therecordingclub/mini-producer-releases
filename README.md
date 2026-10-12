# Mini Producer releases

This repository holds the public, versioned release files for Mini Producer on macOS.

## Current preview

[Mini Producer 2026.10.12-3](https://github.com/therecordingclub/mini-producer-releases/releases/tag/v2026.10.12-3) is an unsigned, unnotarized preview for Apple silicon Macs running macOS 26.2 or later. The app uses an ad hoc signature, and Gatekeeper may block the installer.

The preview requires a licensed Ableton Live 12 installation and OpenAI sign-in. Musical listening also requires an OpenAI API key with available credit, or it can be skipped with musical results left unapproved. Optional Splice and Suno features use the recipient's own accounts.

The release includes the installer, corresponding source archive, SHA-256 checksums, and the portable Franklin's Tower Jam Edit v1.2 Ableton project with its native relocation proof.

## Verify downloads

Download `SHA256SUMS` with the four listed assets, then run:

```sh
shasum -a 256 -c SHA256SUMS
```
