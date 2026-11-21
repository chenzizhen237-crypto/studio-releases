# Studio releases

Downloads and the auto-update feed for **Studio** (`dev.lucas.studio`), the macOS control room for the
Convoy multi-camera system. The source is private; this repo holds only the release builds.

Each release carries:

- `Studio-<version>-arm64-mac.dmg`: drag-to-install disk image
- `Studio-<version>-arm64-mac.zip` and `latest-mac.yml`: the feed App Updater reads

Builds are ad-hoc signed and not notarised. On first launch, right-click the app and choose **Open**.

Releases are published from the source repo with `scripts/release.sh`; nothing is pushed here by hand.
