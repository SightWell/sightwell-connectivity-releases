# Sightwell Connectivity releases

Installers for the Sightwell Connectivity desktop client, published by
MINICLOUD FZCO. This repository holds binaries only; there is no source here.

## What each release contains

- `Sightwell-<version>.pkg`: the macOS installer, signed with MINICLOUD FZCO's
  Developer ID (team `US5JKY7Z7F`) and notarised by Apple.
- `Sightwell-<version>.pkg.sha256`: its SHA-256 checksum.
- `Sightwell-<version>.pkg.sig`: the update signature the client's updater
  checks before it installs the package.
- `version`: the version number the client's update check reads.

The `keys` release (marked as a pre-release, so it never becomes "latest")
holds the updater's artifact public keys and revocation list, each signed by
MINICLOUD FZCO's offline root key.

## Licences

The desktop client is built on NetBird's client (BSD-3-Clause, © NetBird GmbH
and AUTHORS). Each installer carries the licence texts of NetBird and of every
third-party component in `Sightwell.app/Contents/Resources/licenses/`.

Help: https://sightwell.ai/connectivity
