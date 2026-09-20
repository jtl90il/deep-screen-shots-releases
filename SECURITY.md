# Release-channel security

This repository is a public binary-only update channel for Deep Screen Shots.

Allowed release assets:

- Versioned Deep Screen Shots installer (`.exe`)
- Matching installer SHA-256 file (`.exe.sha256`)
- Optional versioned portable package (`.zip`)
- `release-manifest.json`
- Release notes

Source code, project files, PDB symbols, credentials, API tokens, signing certificates, private keys, and signing passwords must never be published here.

The application accepts updates only from HTTPS GitHub release URLs and verifies the downloaded installer against the release checksum before launching it. Production releases should also be Authenticode-signed by Deep Security.
