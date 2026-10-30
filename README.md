# Cyber Stealth releases

Official installer distribution for [Cyber Stealth](https://cyberstealth.link).

This repository contains release notes and downloadable build artifacts, not the private application source or user data. Each published build includes a SHA-256 inventory and source-commit provenance.

## Release channels

**Manual previews** are explicitly marked as GitHub prereleases. They are intended for testing and are not automatically delivered by the stable updater. Read the platform-specific signing notice in the release before installing.

**Stable releases** require the product's signing, verification, and publication gates. A successful compilation or antivirus scan alone is not a trusted publisher signature, Apple notarization, or a production-readiness certification.

Never disable antivirus or operating-system security protections to install a build. A quarantined or unexpectedly changed file must not be installed.

## Verify a download

Compare its SHA-256 with the `SHA256SUMS.txt` file attached to the same release. On Windows, use `Get-FileHash -Algorithm SHA256 -LiteralPath <installer>`; on macOS, use `shasum -a 256 <installer>`.

Only versions listed by the official website's download page are currently offered. Older or withdrawn binaries are not restored automatically.
