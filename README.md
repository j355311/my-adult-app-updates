# My Adult App Updates

This public repository hosts application-only releases for My Adult App.

Install `My.Adult.App.Setup.exe` for a standard per-user Windows installation (not a portable app). After installation, the app's **Update app** button checks the latest stable release, verifies the update package against its SHA-256 checksum, installs it, and restarts the app. Release files contain app code only, not personal videos, pictures, library records, or settings.

Each stable release includes:
- `My.Adult.App.Setup.exe` and its `.sha256` checksum for first-time installation
- `My.Adult.App.Update.zip` and its `.sha256` checksum for in-app updates