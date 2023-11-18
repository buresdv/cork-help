---
layout: default
title: Maintenance Operations
---

While Homebrew usually does a good job keeping itself functional, from time to time, situations might arise that Homebrew can't handle on its own:
1. You uninstalled a package, but not its dependencies.
2. You have installed many large packages.
3. You might have broken something.

Maintenance takes care of such situations and lets you keep Cork and Homebrew alike fast and functional.

## Running Maintenance

You have three ways to initiate the maintenance process:
1. Click **Brew Maintenance…** or **Delete Cached Downloads…** on the [Status Page](/user-interface/detail-area/status-page.html). Both options will show the same window, but **Brew Maintenance** will have the default steps you have set in [Maintenance Settings](/settings/sections/maintenance.html) pre-selected, while **Delete Cached Downloads** will have only the step **Delete cached downloads** pre-selected.
2. Click **Maintenance** in the Menu Bar, then click either **Perform Maintenance…** or **Delete Cached Downloads…**. See above for the explanation of the differences between these two options.
3. Use the keyboard shortcut `⇧ ⌘ M` to open the **Maintenance dialog**, or `⌥ ⌘ M` to open the **Delete cached downloads** dialog. 

## Maintenance Options

You can mix-and-match the following settings, depending on what you want to do:

| Step Name                   | Description                                                  |
| --------------------------- | ------------------------------------------------------------ |
| Uninstall orphaned packages | **Orphan** is a package that was installed as a dependency of another package, and this package is no longer installed.<br />This step removes such packages. |
| Purge Homebrew cache        | Delete cached data stored by Homebrew.                       |
| Delete cached downloads     | Delete leftover files from completed package installations.  |
| Perform health check        | Check if Homebrew is running properly                        |

