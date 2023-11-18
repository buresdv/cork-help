---
layout: default
title: Package Settings
---

This section controls various parts of the [package installation process](/package-operations/workflows/how-to-install-packages.html).

| Setting Name                         | Description                                                  |
| ------------------------------------ | ------------------------------------------------------------ |
| **Search results**                   |                                                              |
| Show package descriptions            | Control whether to load descriptions of packages in search results. |
| **Compatibility**                    |                                                              |
| Check package compatibility          | Check found packages for compatibility with your macOS version. |
| **Advanced**                         | These settings are intended for advanced users only. Changing them might lead to unexpected problems with not only Cork, but Homebrew as a whole. |
| Show real-time outputs of operations | Show real-time Terminal outputs of the underlying Homebrew operations that Cork invokes and responds to.<br />Not all Cork operations support real-time outputs; namely, installing and updating packages, support them, while other operations might be implemented in the future. |
| Show real-time outputs by default    | Control whether the dialog which displays real-time outputs is expanded by default. |
| Enable package purging               | Control whether [purging](/package-operations/advanced/purging.html) is enabled. |
| Clean up after old packages          | Control whether old fields from operations such as updating are deleted when not in used.<br />This option also controls automatic cleanups that occur after you have not used Homebrew for more than 30 days.<br />**Disabling this option might break your Homebrew installation.** |

