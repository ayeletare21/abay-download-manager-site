---
layout: default
title: Open Source Components
description: Source access, notices, licenses, and relinking information for open-source components included with Abay Download Manager.
---

# Abay Download Manager — Open Source Components

Abay Download Manager includes open-source media components distributed under
their respective licenses. This page provides source access and compliance
information for the verified Windows Media V4 component set used by the ADM
Windows 1.0.0 release family. It does not state or imply that the entire ADM
application is licensed under the LGPL.

## Windows Media V4

- Runtime candidate SHA-256: `16d6269e436b7da6a6d1600f7fc7814eab4961e6185ed001fd9f51fce395395c`
- Corresponding source: `ADM-Windows-Media-V4-Corresponding-Source.zip`
- Corresponding-source SHA-256: `323e059077dd52c56b7463d807f43aae4de5eb88f3287a5dc3b33f60bcd3cad8`
- [Download the corresponding-source archive](https://github.com/ayeletare21/abay-download-manager-site/releases/download/windows-media-v4-source-1.0.0/ADM-Windows-Media-V4-Corresponding-Source.zip)
- [View the associated release record](https://github.com/ayeletare21/abay-download-manager-site/releases/tag/windows-media-v4-source-1.0.0)

The download is the exact reviewed source archive associated with the runtime
candidate hash above. Verify the archive's SHA-256 before relying on it.

## Notices and license information

The corresponding-source archive contains the pinned component sources, build
scripts and configuration, source manifest, applicable license texts,
copyright notices, and third-party notices for the reviewed Windows Media V4
set. The Windows application distribution also presents the component
inventory, license texts, notices, and source-access information under
**Settings → About → Third-Party Licenses**.

Each included component remains governed by its own license. In particular,
the Windows player runtime uses dynamically linked LGPL-mode media libraries;
other permissively licensed dependencies retain their respective terms.

## Source and relinking

The archive provides the source and reproducible build information for the
reviewed open-source media components. The LGPL libraries are packaged as
separate dynamically linked DLLs so recipients can replace them with compatible
modified builds, subject to ordinary application integrity and operating-system
security requirements. ADM does not impose a technical restriction intended to
prevent replacement of those LGPL libraries or debugging of modifications.

For questions about this source package, use the [ADM support
channel](https://github.com/ayeletare21/abay-download-manager-site/issues).
