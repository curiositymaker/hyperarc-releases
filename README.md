# HyperArc Releases

Public release channel for [HyperArc](https://hyperarc.app) — semantic search
for your video library on macOS.

The application source code is in a separate, private repository. This repo
exists only to host release artifacts and the Sparkle auto-update feed.

## Download

Grab the latest DMG from the [Releases page](https://github.com/curiositymaker/hyperarc-releases/releases/latest).

Installing HyperArc requires a license key — [purchase one on the website](https://hyperarc.app/pricing).

## Auto-updates

Installed copies of HyperArc poll [`appcast.xml`](appcast.xml) in this
repository once per day and prompt users to install new versions via
[Sparkle](https://sparkle-project.org). Every release is:

- Signed with Apple Developer ID — `Developer ID Application: Manav Lakhadive (QAYP7277VG)`
- Notarized and stapled by Apple
- EdDSA-signed with the Sparkle update key (public key bundled in the app)

The appcast is served via raw.githubusercontent.com and the DMGs via GitHub's
release asset CDN, so both are publicly fetchable without authentication.

## Support

Open issues via the regular HyperArc support channels — see
[hyperarc.app](https://hyperarc.app). This repository's issue tracker is
disabled because it hosts release artifacts, not code.
