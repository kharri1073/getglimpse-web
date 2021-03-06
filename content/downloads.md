---
title: "Downloads"
date: 2020-09-08T08:45:00+01:00
draft: false
menu: "main"
---
The latest release is Glimpse Image Editor 0.2.0. It is based on the [GNU Image Manipulation Program](https://www.gimp.org/) 2.10.18, and is provided under the terms of the GNU General Public License v3. [Release Notes](/posts/glimpse-0-2-0-release-notes/)

#### Quick Download Links
[Windows](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0-i686.msi) (Recommended) | [Windows](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0-x64.msi) (64-bit with G'MIC) | [Linux](https://www.flathub.org/repo/appstream/org.glimpse_editor.Glimpse.flatpakref) (Flatpak)

### Windows
Glimpse Image Editor 0.2.0 is supported on 32-bit and 64-bit systems running Windows 7 or later. If you experience problems during installation, you should review the [Known Issues](https://github.com/glimpse-editor/Glimpse/wiki/Known-Issues-%28Windows%29) page before reporting a bug.

If you do not know which installer to download we recommend that you choose the 32-bit one, as it is compatible with the widest range of systems.

#### Glimpse Image Editor 0.2.0 Installer
This installs a 32-bit version of Glimpse Image Editor 0.2.0. You should choose this option if you are upgrading an existing Glimpse Image Editor 0.1.2 installation and/or need compatibility with existing third-party plugins.

**glimpse-0.2.0-i686.msi** (189 MB) | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0-i686.msi) | *Sha256: 2163403ca13d27be399b7fc1348719b2a9a4ddc4bc8c4b00aa8edd608bacfdbd*

You can download previous versions of Glimpse Image Editor for Windows [from Github](https://github.com/glimpse-editor/Glimpse/releases/).

#### Glimpse Image Editor 0.2.0 (64-bit) Installer
This installs a native 64-bit version of Glimpse Image Editor 0.2.0 with [G'MIC](https://gmic.eu/). You should choose this option if you know you are running a 64-bit version of Windows and do not need to upgrade an existing Glimpse Image Editor 0.1.2 installation.

**glimpse-0.2.0-x64.msi** (304 MB) | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0-x64.msi) | *Sha256: 420dbbe11fef2a1d741083eb72f99732b9aec620d1d8274f9fb7a30e650030ff*

Support for legacy 32-bit plugins is still experimental with the 64-bit Windows installer. You should [review our wiki](https://github.com/glimpse-editor/Glimpse/wiki#third-party-plugin-installation-guides) before reporting any bugs.

#### External Download Mirrors
These servers are not directly supported by us, and are maintained by third party developers. We strongly recommend running a virus scan on your system whenever you download the Glimpse Image Editor 0.2.0 installer from these sources.

* Repositories: [Chocolatey](https://chocolatey.org/packages/glimpse/) | [WinGet](https://winget.run/pkg/Glimpse/Glimpse)
* Direct downloads: [Softpedia](https://www.softpedia.com/get/Multimedia/Graphic/Graphic-Editors/Glimpse-Image-Editor.shtml) | [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/)

### Linux
We distribute Glimpse Image Editor 0.2.0 on Flathub for end users. We also partially support Canonical's [Snap Store](https://snapcraft.io/glimpse-editor/).

To assist users of some Linux distributions, an AppImage is being developed. [#108](https://github.com/glimpse-editor/Glimpse/issues/108)

#### Flatpak
If `flatpak` is not already installed on your machine, follow these instructions: https://flatpak.org/setup/

##### Installing from Flathub
You can find Glimpse Image Editor by searching in your distribution's software center, or you can [click on this link](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) from Flathub.

Alternatively you can install it manually at the command line:
```
$ flatpak install flathub org.glimpse_editor.Glimpse
```

##### Installing from other third-party Flatpak repositories
If you would prefer to use your own third party repository for dependency resolution instead of Flathub, we also provide a [single-file bundle](https://docs.flatpak.org/en/latest/single-file-bundles.html):

**glimpse-0.2.0.flatpak** (49.4 MB) | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0.flatpak) | *Sha256: 9f53758d5d572ef0ff4159862cc70bd4a2b80e4201e93b7f35c9ca62541f16a8*

To install the single-file bundle at the command line:
```
$ flatpak install glimpse-0.2.0.flatpak
```

#### Community-supported sources
These builds are provided by third parties in the wider Linux community. We do not create, package or directly support these sources, so if you raise any bugs for them that would not apply to most Linux users, we may direct you elsewhere to get the issue fixed.

* [`glimpse-editor`](https://snapcraft.io/glimpse-editor/) @ Snap Store for [Ubuntu](https://ubuntu.com/) (and [others](https://snapcraft.io/about))
* [`glimpse-editor-git`](https://aur.archlinux.org/packages/glimpse-editor-git/) @ AUR repository for [Arch](https://www.archlinux.org/) and [Manjaro](https://manjaro.org/)
* [`media-gfx/glimpse`](https://gitweb.gentoo.org/repo/proj/guru.git/tree/media-gfx/glimpse) @ Guru repository for [Gentoo](https://www.gentoo.org/)
* [`glimpse:IBboard`](https://software.opensuse.org//download.html?project=home%3AIBBoard%3Adesktop&package=glimpse) @ Open Build Service for [OpenSUSE](https://www.opensuse.org/)

### MacOS
Unfortunately Glimpse Image Editor is not supported on MacOS. We recommend either running the Windows version in a virtualized environment or sticking with the [GNU Image Manipulation Program](https://www.gimp.org/downloads/). 

You may also be interested in trying [Seashore](https://apps.apple.com/us/app/seashore/id1448648921?mt=12), an older fork of the GNU Image Manipulation Program designed specifically for MacOS. While it does have fewer features, it may still be suitable for your intended use case.

We are investigating the possibility of distributing Glimpse Image Editor through [HomeBrew](https://brew.sh/), a popular third-party package manager for macOS. [#402](https://github.com/glimpse-editor/Glimpse/issues/402)

### Build our code
We have provided instructions for building and packaging the Glimpse Image Editor source code on our project wiki: https://github.com/glimpse-editor/Glimpse/wiki

You can also test out our own beta and development releases by following these instructions: https://github.com/glimpse-editor/Glimpse/wiki#testing
