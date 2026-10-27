# TCT Exam Editor — Public Releases & Update Manifests

This repository is the official, public binary-only distribution channel for **TCT Exam Editor**.

> **Note**: The application source code remains private in `nguyendinhoa568-prog/tct-exam-editor`. This repository contains only compiled release binaries, release notes, and cryptographically signed update manifests (`latest.json`).

## Security Architecture
- Updates are authenticated using Ed25519 signed manifests (`latest.json`) verified against pinned publisher public keys embedded inside the installed application.
- All downloads are validated against SHA-256 digests and exact byte sizes before handoff.
- Release assets are hosted immutably via GitHub Releases.
