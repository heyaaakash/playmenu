# PlayMenu 1.4.6 — build 15

## Downloads

- [Apple Silicon ZIP](https://github.com/heyaaakash/playmenu/releases/download/v1.4.6/PlayMenu-1.4.6-macos-arm64.zip)
- [Intel ZIP](https://github.com/heyaaakash/playmenu/releases/download/v1.4.6/PlayMenu-1.4.6-macos-x86_64.zip)
- [SHA-256 checksums](https://github.com/heyaaakash/playmenu/releases/download/v1.4.6/SHA256SUMS.txt)
- [Build provenance](https://github.com/heyaaakash/playmenu/releases/download/v1.4.6/BUILD_INFO.txt)

## Changes

- Added an optional private playlist to sync Liked Songs and play the selected song in playlist order. Reconnect Spotify and allow private playlist editing to set it up.
- Added album playback as a fallback when Spotify does not start a liked-song list. The next song may come from the album when this fallback is used.
- Fixed an error shown after successful Next and Previous commands.

The private playlist is updated on sync; edits made directly to it may be overwritten. Local and unsupported tracks are skipped. Packages are ad-hoc signed and not notarized. Intel is cross-compiled; physical Intel runtime remains unverified.
