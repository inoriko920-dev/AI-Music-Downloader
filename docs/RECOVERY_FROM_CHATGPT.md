# Recovery notes from ChatGPT/Library

Date: 2026-10-01

This repository is a recovery target after the previous GitHub account became unavailable.

## Known previous repository

- migrated repository: `tonitaru6-cloud/AI-Music-Downloader`

Chat history records that 81 source files were copied during migration and a migration commit beginning `52d7778` was reported.

## Recovered build manifest

A surviving `VERSION_MANIFEST.json` records:

- app: AI Music Downloader
- source git SHA: `b1b7c37062284bcf1a8b011ec2ebef7ed9fbe7a8`
- built at: `2026-09-29T12:02:47.2185962Z`
- app version: `1.0.0-rc2`
- Python: `3.11.9` AMD64
- PySide6: `6.11.2`
- yt-dlp: `2026.8.19`
- yt-dlp-ejs: `0.8.0`
- spotdl: `4.5.2`
- mutagen: `1.48.1`
- PyInstaller: `6.22.3`
- FFmpeg: `9.0`
- Deno: `2.9.7`

The manifest also preserves SHA-256 values for release lock/config files and tool binaries.

## Portable artifact recovered

A Windows portable package has been recovered. It includes the executable, `_internal` runtime, FFmpeg/FFprobe, Deno, release-info, data/download folders, and third-party notices.

Important: many `.py` files inside the frozen package belong to bundled dependencies such as spotDL/pykakasi. Their presence does not prove that the application's original source tree is fully recovered.

## Recovery rule

Use source SHA `b1b7c37062284bcf1a8b011ec2ebef7ed9fbe7a8` as a key identity when searching local clones, old archives, restored GitHub access, or other ChatGPT files. Compare reconstructed behavior against the recovered portable build before declaring recovery complete.
