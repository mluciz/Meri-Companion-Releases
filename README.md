# Meri Companion — Windows releases

This repository is the **public binary distribution channel** for the Windows Meri Companion research application. Its private development source code, research data, user memories, GPU credentials and update-signing private keys are **not** published here.

## Current status

The release channel is being configured. **No installable signed release is published yet.** Until a first release is available, download previews only from the private source project's GitHub Actions artifacts if you have authorized access.

When active, each versioned GitHub Release will contain:

- a Windows x64 NSIS installer (`.exe`),
- its Tauri updater signature (`.exe.sig`),
- a `latest.json` manifest pointing to the signed installer.

Tauri's updater verifies the signature before installing an update. The initial install is manual; future releases are checked inside the app.

**Important:** Tauri updater signing is not the same as Windows Authenticode publisher signing. Installers may still show an unknown-publisher warning until separately code-signed. Do not disable Windows security protections.

## Releases

[See published releases](https://github.com/mluciz/Meri-Companion-Releases/releases)

Only compiled release artifacts and public release notes belong here. Do not upload source archives, checkpoint weights, personal information, secrets, or the private updater signing key.

The research map is an **unverified, human-inspired computational ontology**; it does not establish that the app has human feelings, consciousness or an independently verified general intelligence.
