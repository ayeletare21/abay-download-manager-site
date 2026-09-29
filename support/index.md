---
layout: default
title: Support
description: Installation, browser integration, downloads, Library, Player, and Media Studio support for Abay Download Manager.
---

# Abay Download Manager Support

- Publisher: Abay Software
- Support contact: [GitHub Issues](https://github.com/ayeletare21/abay-download-manager-site/issues)
- Website: [https://ayeletare21.github.io/abay-download-manager-site/](https://ayeletare21.github.io/abay-download-manager-site/)
- Support URL: [https://ayeletare21.github.io/abay-download-manager-site/support/](https://ayeletare21.github.io/abay-download-manager-site/support/)

## Install ADM

Obtain ADM only from the owner-approved website or distribution channel once it
is published. Install and launch the desktop application before installing a
browser extension. Production packages and their bundled native messaging host
must be correctly signed and, where required, notarized by the publisher.

If the operating system blocks a production ADM component, do not run Terminal
commands or remove quarantine attributes. Treat that as a release/support issue
and contact the publisher through the support channel above.

## Connect a browser

ADM v1 supports Google Chrome, Microsoft Edge, and Mozilla Firefox. Safari is
not included in ADM v1.

1. Open ADM.
2. Open **Settings → Browser Integration**.
3. Find the browser you use and choose **Install Extension**.
4. Complete installation on that browser's official extension store page.
5. Return to ADM and allow the extension and app a moment to connect locally.

The ADM desktop application must be installed and running for extension
downloads. Production setup never requires Developer Mode, Load unpacked,
`about:debugging`, extension IDs, manual native-host files, or Terminal commands.

## Browser connection states

- **Connected** — the extension completed a live, compatible handshake with
  ADM. Browser handoff is ready.
- **Native host ready** — ADM prepared its local browser connection, but the
  extension is not currently connected. Install or start the extension.
- **Extension not installed** — choose **Install Extension** to open the
  browser's official listing.
- **Needs repair** — choose **Repair Integration**. ADM recreates only its own
  native-host configuration.
- **Protocol mismatch** — the app and extension versions are incompatible.
  Update both from their official distribution channels, then restart them.

ADM does not silently install, enable, remove, or update browser extensions.
Those actions remain under browser/store control.

## Start and manage downloads

On a compatible supported media page, choose **ADM ↓**, select an available
quality, and confirm the download in ADM. Availability varies by page, source,
format, and access. For compatible ordinary HTTP/HTTPS files, ADM may offer a
handoff while keeping the browser as a fallback.

Downloads use ADM's configured category folder by default. The confirmation
dialog shows the destination and can offer a custom folder. ADM does not
silently overwrite an existing file.

Use Downloads to monitor progress and control supported pause, resume, retry,
queue, scheduling, and bandwidth behavior. A server that does not support safe
resume may require a restart.

## Import and Library

Use Library's import action to select supported local video, audio, or image
files. Import adds metadata and a reference; it does not move or rewrite the
source file. On macOS, ADM uses the operating system's security-scoped file
permission mechanism to retain access to user-selected locations.

Library organizes completed and imported items and provides open, reveal,
playback, and edit actions where supported. Removing an imported item from
Library does not delete its original file.

## Player and Media Studio

The built-in Player supports compatible Library video and audio, including
play/pause, seek, volume, playback speed, keyboard controls, and fullscreen for
video.

Media Studio creates non-destructive projects. Editing decisions do not rewrite
the original source. Supported projects can include trimming, cutting,
splitting, audio changes, clip arrangement, visual adjustments, transitions,
and text or image overlays. Export uses a save dialog and creates a new media
file at the selected destination.

## Common problems

### The extension says ADM Retry or cannot connect

Launch ADM, check **Settings → Browser Integration**, and wait for the current
browser status. If it shows **Needs repair**, choose **Repair Integration**. If
it shows **Extension not installed**, install from the official store link.

### Install Extension does not open a listing

The production app requires a configured official listing URL for that browser.
If no listing opens in a published build, contact support; do not use a
developer/sideloaded extension as a production workaround.

### A media page has no ADM control or no compatible quality

Confirm the page is publicly accessible in the current browser session and the
media is playing or loaded. Not every page, representation, or protected stream
is supported. ADM does not bypass DRM or access controls.

### A download stays in the browser

ADM deliberately releases unsupported, non-reproducible, cancelled, or failed
handoffs back to the browser. Confirm ADM is connected and review the download
confirmation when it appears.

### An imported file is missing

The original may have been moved, renamed, deleted, or become inaccessible.
Restore the file or use Library to select/import it again. ADM does not keep a
hidden copy of imported source media.

### Playback or export is unavailable

Confirm the source still exists and uses a supported media format. Choose a
writable export destination with the format offered by ADM. The original source
remains unchanged if preparation or export fails.

## Contact support

- Support: [GitHub Issues](https://github.com/ayeletare21/abay-download-manager-site/issues)
- Website: [Abay Download Manager]({{ '/' | relative_url }})
- Publisher: Abay Software
