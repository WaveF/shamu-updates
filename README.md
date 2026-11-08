# Shamu Updates

This repository hosts **only** Shamu update metadata and release assets.

- The application source is private and is **not** published in this repository.
- Update manifest: `updates/stable.json`
- Release binaries: GitHub Releases

The Shamu application reads the manifest over HTTPS, verifies the Ed25519 signature against the public key embedded in the app, then downloads the matching release asset.
