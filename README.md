# EM Automation Hub — Windows downloads

This repository distributes official Windows binaries only. Application and
license-server source code are maintained in private repositories.

## Download

[Download the latest EXE](https://github.com/pakistaniforum12345-wq/em-hub-releases/releases/latest/download/EMAutomationHub.exe)

[Release notes and SHA256 checksum](https://github.com/pakistaniforum12345-wq/em-hub-releases/releases/latest)

Use Windows 10/11 (64-bit). Keep the EXE in a writable folder. FFmpeg and FFprobe
must be installed separately or configured in the app. The first launch may take
longer while the portable EXE extracts its bundled dependencies. Optional AI
features may download model files on first use.

Internet access is required for license verification, stock image search and
the required-update check. Existing license/activation rules apply. Pixabay
search uses the server-side service; no shared provider key is distributed.

## Updates

Packaged v39.1.0+ checks the latest published release at startup and periodically
while running. A newer release requires an update before continuing. Existing
older builds may need this baseline installed manually. Download this EXE if
an old build cannot access its previous update channel.

Only the EXE and its `.sha256` checksum are product release assets. GitHub's
automatically generated source archives contain this download README, not the
application source. Binaries can be reverse-engineered; they are not secret
storage.
