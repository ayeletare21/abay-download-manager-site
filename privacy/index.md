---
layout: default
title: Privacy Policy
description: Privacy information for Abay Download Manager and its optional browser extensions.
---

# Abay Download Manager Privacy Policy

This policy has been approved by the owner for publication.

- Effective date: September 29, 2026
- Publisher: Abay Software
- Contact: [GitHub Issues](https://github.com/ayeletare21/abay-download-manager-site/issues)
- Website: [https://ayeletare21.github.io/abay-download-manager-site/](https://ayeletare21.github.io/abay-download-manager-site/)
- Privacy URL: [https://ayeletare21.github.io/abay-download-manager-site/privacy/](https://ayeletare21.github.io/abay-download-manager-site/privacy/)

## Scope

This policy describes Abay Download Manager version 1 and its optional Chrome,
Microsoft Edge, and Firefox browser extensions and local native messaging host.
ADM is a local-first desktop application for downloading, organizing, playing,
and editing compatible files and media.

## Information stored locally

ADM stores operational information on the user's device so requested features
can work and recover state. Depending on use, this can include:

- Download URLs, filenames, destinations, status, progress checkpoints, resume
  validators, errors, queues, schedules, and download history.
- Library MediaAsset metadata such as the local path/reference, display name,
  type, size, duration, format, dimensions, and thumbnail reference.
- Media Studio project state, including selected source assets and edit
  decisions.
- Browser-integration configuration, health/version information, and bounded
  active-capture state.
- Application preferences.
- On macOS, security-scoped bookmark data needed to retain user-authorized
  access to files or folders selected through the operating-system picker.

This local data is not automatically uploaded to an Abay cloud account. ADM v1
does not provide an Abay account or cloud-sync service. Operating-system backup,
device synchronization, security, and retention settings may independently
apply to data on the user's device. Files remain local unless the user
deliberately shares them or uses another external service independently.

## Browser extension and network observation

The optional browser extension declares HTTP/HTTPS page and request access so
it can offer the **ADM ↓** control on eligible media, build a compatible quality
catalog, associate cross-origin media requests with the active page or post,
and coordinate compatible ordinary browser downloads.

This means the extension may observe relevant HTTP/HTTPS page, request,
response, redirect, and browser-download information locally. The purpose is
limited to media/download detection, source reacquisition, and a
user-requested handoff to ADM. This capability should not be described as ADM
recording all browsing history.

After an explicit user action, the extension may send the locally installed
ADM app bounded page/media metadata, logical media identity, operational source
information, and request context needed for the selected source. Request
context may include transient browser session headers such as Cookie or
User-Agent. The extension does not request the browser history, cookies, or
form-data APIs.

The browser extension communicates with the local ADM desktop application using
the browser's native messaging mechanism. This communication occurs on the
device; it is not an Abay cloud service.

## Cookies, signed sources, and transient data

ADM does not persist browser cookies as source identities or import them into a
durable credential store. Transient request context is used only when needed to
perform the user's selected operation.

For logical media sources that require reacquisition, ADM stores a stable page,
post, media, or representation identity rather than a short-lived signed CDN
URL. Operational manifests, authorization material, and signed/expiring media
URLs are kept out of durable ADM source persistence where this architecture
applies. Bounded browser capture state expires; it is not a permanent browsing
record.

## Downloads, imported files, and exports

Downloaded files are written to ADM's configured category destination or a
folder explicitly selected by the user. Network requests go directly to the
website or download host selected by the user, which can observe ordinary
connection information under its own privacy practices.

Importing media adds a local reference and metadata to Library; it does not
upload the file or move it from the selected location. ADM's non-destructive
editor stores project decisions without rewriting the original imported source.
Export creates a new file at a user-selected destination.

## Retention and deletion

ADM does not define one fixed automatic retention period for all local download
history, Library metadata, editor projects, preferences, or files. These items
remain locally until the user removes them through available ADM or operating-
system controls, clears application data, deletes the file, or uninstalls the
application, subject to operating-system backups.

Removing an item from Library removes its Library record and does not delete the
original imported file. Removing download history and deleting a downloaded
file are separate actions. Interrupted or cancelled partial files may remain
according to the active download policy so the user can inspect or resume work.

Because the publisher does not receive local-only records or files, it cannot
delete data that remains solely on the user's device.

## Analytics, advertising, and sale of data

ADM v1 contains no configured telemetry, analytics, advertising, or automatic
crash-upload service. The publisher does not sell or rent personal data obtained
through ADM. If these practices change, the policy and store disclosures must
be updated before the changed behavior ships.

## Chrome Web Store Limited Use

The use of information received through the Abay Download Manager browser
extension will comply with the Chrome Web Store User Data Policy, including the
Limited Use requirements.

## Diagnostics and support

Diagnostic export is initiated by the user and is designed to omit URLs,
credentials, private paths, and file contents. Users should review diagnostics
before deliberately sharing them with support. ADM does not automatically
upload diagnostics.

## Third-party websites and services

Third-party websites, browsers, download hosts, and operating-system services
have their own terms and privacy practices. ADM is not affiliated with or
endorsed by YouTube, Facebook, Rumble, TikTok, X/Twitter, Google Chrome,
Microsoft Edge, or Mozilla Firefox. Their product names and trademarks belong
to their respective owners.

## Content and user responsibility

ADM does not implement DRM or protected-stream bypass, access-control bypass,
paywall bypass, or credential theft. Users are responsible for ensuring they
have the right or permission to download, edit, export, and use content.

## Children

ADM is a general-purpose utility and is not directed to children. The owner
must adapt this section if legal review or selected distribution regions require
different language.

## Changes and contact

Material changes should be published at the public Privacy Policy URL with an
updated effective date as required by applicable law or store policy.

- Publisher: Abay Software
- Support: [GitHub Issues](https://github.com/ayeletare21/abay-download-manager-site/issues)
- Website: [Abay Download Manager]({{ '/' | relative_url }})
