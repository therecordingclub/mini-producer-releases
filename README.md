# Mini Producer releases

This repository holds the public, versioned release files for Mini Producer on macOS.

## Release status

No installer is publicly available yet. The current preview is undergoing additional runtime validation.

The planned preview targets Apple silicon Macs running macOS 26.2 or later. It requires a licensed Ableton Live 12 installation and an OpenAI account. Musical listening also requires an OpenAI API key with available credit, or it can be skipped with musical results left unapproved. Optional Splice and Suno features use the recipient's own accounts.

Preview builds remain unsigned and unnotarized until Developer ID signing and notarization are complete. The app uses an ad hoc signature, and Gatekeeper may block the installer.

## Verify downloads

Published releases include `SHA256SUMS`. After downloading all three files into one directory, run:

```sh
shasum -a 256 -c SHA256SUMS
```

