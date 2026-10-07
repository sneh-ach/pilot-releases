# Pilot releases

**Present freely.**

This repository is the **public Mac and Windows installers** for Pilot Desktop, plus `latest.json` for the in-app updater.

Source is private. Pairing is not on GitHub, and it is not on the website. After you pair, the phone talks to the computer on the local network.

Site: [present-freely.vercel.app](https://present-freely.vercel.app)

## Downloads

Installers live on the [Releases](https://github.com/sneh-ach/pilot-releases/releases) page.

Until a release is **published** (not left as a draft), strangers cannot download it. The website will keep saying “Ships with the first release” until then.

| You have | You download | You do not download |
| --- | --- | --- |
| A Mac | `Pilot.dmg` (universal) | An App Store remote |
| A Windows PC | `Pilot Setup.exe` | A Microsoft Store remote |
| An iPhone or Android | Nothing from this repo | A store app |

The phone remote is a page the desktop app serves after a session starts. That is why there is no iOS or Android binary here.

## Install

The longer notes are on the site: [Install](https://present-freely.vercel.app/docs/install) · [macOS](https://present-freely.vercel.app/docs/macos) · [Windows](https://present-freely.vercel.app/docs/windows)

### macOS

1. Open the `.dmg` and drag Pilot into Applications.
2. The first time, **right-click → Open**. Gatekeeper blocks unsigned builds until you do.
3. Open the deck, then Start Session in Pilot.
4. Allow **Accessibility** when macOS asks. Pilot needs it for the pointer and for apps that only listen to the keyboard. It does not ask for camera, microphone, or screen recording.

### Windows

1. Run the setup `.exe`.
2. SmartScreen may warn on an unsigned build. That is the operating system, not a broken file.
3. Open the deck, then Start Session in Pilot.
4. Windows does not have an Accessibility prompt.

These builds have not been notarized by Apple or signed with Authenticode. Signing is extra. It is not required to try Pilot on your own machine.

## Pairing

1. Join the **same Wi‑Fi** as the computer (or a hotspot both use).
2. Scan the code Pilot shows, or type the six-digit PIN.
3. Walk. The right side of the phone is Next.

The address on the phone will look like `192.168…`. That is the computer in the room, not this repository. A hotel network that isolates devices will block pairing; the website cannot fix that.

Do not send a PIN, a pairing URL, notes, or a deck to this repo.

## Updates

Installed copies of Pilot Desktop may check [`latest.json`](https://github.com/sneh-ach/pilot-releases/releases/latest/download/latest.json) on this repository. That check uses the internet. Pairing does not. Notes and slides are not part of it.

There is no update notice while this file does not exist.

## What this repository is not

- Not the source
- Not a live session
- Not an account or a cloud remote
- Not a place to open issues (the tracker is off on purpose)

Docs, troubleshooting, and contact: [present-freely.vercel.app](https://present-freely.vercel.app)
