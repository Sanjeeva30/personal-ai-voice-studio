# Personal AI Voice Studio

Local macOS voice studio. This repository hosts installers, signed update metadata, and release notes.

[Download releases](https://github.com/Sanjeeva30/personal-ai-voice-studio/releases)

## Install

Requires Apple Silicon and macOS 27 or later. Download the DMG, quit the app, and drag Personal AI Voice Studio into Applications. This development build is ad-hoc signed; it has no Apple Developer ID signature or notarization.

## Updates

Use Settings → Check for Updates, or the app menu. Sparkle verifies Ed25519 signatures on the feed and downloaded archive before installation and relaunch. Checks are manual, with no system profiling or background polling. Normal voice work stays local.

Versions 0.1.1 and earlier require one initial installation of an updater-enabled release. Projects, models, references and exports are stored outside the application bundle.

## Development status

Tested on an M1 with 16 GB memory. Clean-machine and 8 GB acceptance, human voice-identity quality, Sinhala synthesis and romanization, and cross-language identity are not established. Model weights are installed separately under their respective terms.

Third-party notices, licenses, and corresponding LGPL helper sources are included in the app under Contents/Resources/Documentation. The original personal design archive and private media are not published here.
