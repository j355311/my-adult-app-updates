# My Adult App Updates

This public repository hosts application-only releases for My Adult App.

Run `My.Adult.App.Setup.exe` for a standard Windows installation (not portable). It installs the program to `D:\My Adult App` and stores the app's library and settings in `Documents\My Adult App`. The target computer needs a D: drive. In-app updates download a SHA-256-verified app-code patch, request Windows permission when needed to update D:, then restart the app. Release assets do not include personal videos, pictures, library records, or settings.

Each stable release includes:
- `My.Adult.App.Setup.exe` and its `.sha256` checksum for first-time installation
- `My.Adult.App.Update.zip` and its `.sha256` checksum for in-app updates