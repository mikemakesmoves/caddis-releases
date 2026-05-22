# Caddis Releases

Public binary artifacts for [Caddis](https://caddis.app).

The Caddis source repo (`cadmium`) is private. This repo exists so the
auto-update client can fetch installers without auth.

## Tags in this repo

- **`vX.Y.Z`** — app releases, published by CI on tag push to `cadmium`.
  Each release attaches `.dmg`, `.zip`, `.blockmap`, and the `latest-mac.yml`
  manifest that electron-updater clients read.
- **`ffmpeg-bundle-*`** — static ffmpeg + ffprobe binaries that Caddis
  bundles. Mirrored here so CI doesn't depend on third-party DNS.
