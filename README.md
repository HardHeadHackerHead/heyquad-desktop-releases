# Hey Quad for Desktop

The Hey Quad desktop app: your Hey Quad business line on your computer. Make and
receive calls, send texts, and see your call history and voicemail without
keeping a browser tab open.

This repository holds **release downloads only**. It contains no source code.
Installed copies of the app check here for new versions and update themselves.

## Download

| Platform | Download |
| --- | --- |
| Windows 10/11 (64-bit), recommended | [HeyQuad-x64.msi](https://github.com/HardHeadHackerHead/heyquad-desktop-releases/releases/latest/download/HeyQuad-x64.msi) |
| Windows, per-user install (no admin rights needed) | [HeyQuad-x64-setup.exe](https://github.com/HardHeadHackerHead/heyquad-desktop-releases/releases/latest/download/HeyQuad-x64-setup.exe) |

Every version, with its notes and checksums (`SHA256SUMS.txt`), is on the
[Releases](https://github.com/HardHeadHackerHead/heyquad-desktop-releases/releases) page.

Install one of the two Windows packages, not both. The `.msi` installs for
everyone on the computer and asks for administrator approval; the `.exe`
installs only for you.

> **Windows SmartScreen.** The installers are not yet Authenticode-signed, so
> Windows may show "Windows protected your PC". Choose **More info → Run
> anyway**. Updates are still cryptographically signed and checked by the app
> before it installs them.

## System requirements

- Windows 10 (version 1809 or later) or Windows 11, 64-bit (x64).
- Microsoft Edge WebView2 runtime. It ships with Windows 11; the installer
  adds it on Windows 10 if it is missing.
- A microphone and speakers or a headset for calls.
- An internet connection and a Hey Quad account with an extension.

## Updates

The app checks for a new version when it starts and every few hours. When one
is ready, a small bar says **Update available — restart to update**. It never
interrupts a call: the bar stays hidden while you are on a call, and the update
installs only when you choose **Restart**. You can also check by hand in
**Settings → App updates**.

## Help

Visit [heyquad.com/support](https://heyquad.com/support).

---

© 2026 HEY QUAD LLC. All rights reserved.
