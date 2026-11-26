# Firefly DJ

Firefly DJ is a desktop app for laptop DJs. Paired with the [Firefly cable](https://www.amazon.com/dp/B09XPCJVJ3), it sends the main mix to your speakers, the cue mix to your headphones, and your mic to the room — so you can play out without a mixer.

**Website:** [fireflydj.com](https://fireflydj.com)

This repository hosts installer downloads only. It does not contain the app’s source code.

## Downloads

The latest installers are on the [Releases](https://github.com/Gratitopia/firefly-dj-releases/releases/latest) page.

- **Mac (Apple Silicon):** `Firefly-DJ-mac-arm64.dmg` — signed and notarized by Apple
- **Windows (x64):** `Firefly-DJ-Setup-x64.exe` — also a portable `Firefly-DJ-win-x64.zip`
- **Linux (x86_64):** `Firefly-DJ-linux-x86_64.AppImage`

SHA-256 checksums for each file are in `SHA256SUMS.txt` on the same release.

## Install notes

### Mac

1. Download the `.dmg`, open it, and drag **Firefly DJ** into Applications.
2. If an older test copy is running, quit it first.
3. Allow microphone access when asked.

The Mac app is signed and notarized, so macOS should open it without an “unidentified developer” warning.

### Windows

1. Run `Firefly-DJ-Setup-x64.exe`.
2. Windows SmartScreen may warn that the app is unrecognized (this Windows build is not yet code-signed). Click **More info**, then **Run anyway**.
3. Portable alternative: unzip `Firefly-DJ-win-x64.zip` and run the app from that folder.

### Linux

```bash
chmod +x Firefly-DJ-linux-x86_64.AppImage
./Firefly-DJ-linux-x86_64.AppImage
```

## In the app

Recordings are saved to `Music/Firefly DJ Recordings`. Press `?` for keyboard shortcuts.

The Firefly cable is sold separately: [amazon.com/dp/B09XPCJVJ3](https://www.amazon.com/dp/B09XPCJVJ3).
