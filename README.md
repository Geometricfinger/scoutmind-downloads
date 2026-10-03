# ScoutMind desktop downloads

This is the official binary-only download repository for the ScoutMind desktop
beta. ScoutMind organizes hunting-camera photos and videos, reviews suggested
animal matches, and can work with owner-selected live sources. It is not limited
to one animal species.

## Download

Use the [Releases](https://github.com/Geometricfinger/scoutmind-downloads/releases)
page. A beta release is published only after its Mac and Windows packages pass
the project's native build and validation gates.

Each public beta release provides:

- an Apple silicon Mac ZIP for macOS 14 or later;
- a portable x64 Windows ZIP for Windows 10 version 1809 or later and Windows 11;
- `START_HERE.md` with installation and activation steps;
- `SHA256SUMS.txt` and `release-manifest.json` for byte-level verification.

ScoutMind is a one-time-license product with no subscription and no ScoutMind
account. The core camera library stays on the owner's computer. Optional online
features contact only the services the owner chooses and configures.

The beta is not Apple-notarized or Windows code-signed. The release instructions
explain the one-time macOS and Windows approval steps honestly. Keep original
camera files and make a verified backup while testing.

ScoutMind suggests possible identity matches; the owner makes the decision. A
beta package is functional validation, not a promise of field recognition
accuracy or Store certification.

## Repository scope

This repository contains customer downloads and their verification manifests.
It does not contain the private application source, signing keys, licence files,
customer data, diagnostics, seller tools, or test databases.

The complete corresponding source offered for the bundled FFmpeg and OpenCV
FFmpeg components is maintained separately at
[Geometricfinger/scoutmind-third-party-source](https://github.com/Geometricfinger/scoutmind-third-party-source).
