# Kerlyss Release

Official release distribution repository for **Kerlyss**.

This repository stores **release artifacts only** (not source code): installers/packages, checksums, and release notes.

## What You Will Find

- Windows release artifacts (e.g. `.exe`, `.msix`, portable archives)
- Android release artifacts (e.g. `.apk`, optional `.aab` for internal tracks)
- iOS distribution references (TestFlight/App Store notes, optional enterprise/internal links)
- Versioned release notes
- SHA256 checksums for integrity verification

## Download

Use the **Releases** page for official downloads:
- Windows: direct download from release assets
- Android: direct APK download from release assets
- iOS: install through TestFlight/App Store (recommended)

## Install

### Windows
1. Download latest Windows asset from Releases.
2. Verify checksum (recommended).
3. Run installer or extract archive.
4. Launch Kerlyss.

### Android
1. Download latest APK from Releases.
2. Verify checksum (recommended).
3. Enable install from trusted source (if needed).
4. Install and open Kerlyss.

### iOS
Use TestFlight/App Store distribution channel linked in release notes.

## Integrity Verification (SHA256)

Each release includes `checksums.txt`.

Example:
```bash
# Windows (PowerShell)
Get-FileHash .\kerlyss-windows-x64-setup.exe -Algorithm SHA256

# Compare output with checksums.txt
