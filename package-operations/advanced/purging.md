---
layout: default
title: Package Purging

---

Unlike a normal uninstall, purging a package removes all files associated with a package, even those that might be in use by other packages; as long as a file is used by a package that's purged, it will get removed. This can lead to Homebrew breaking if you remove the wrong package. Therefore, purging is disabled by default.

## Enabling Purging

To enable purging, go to **Settings → Package** and check **Enable package purging** under the **Advanced** section.

To learn more, see [Package Settings](/settings/sections/packages.html)

## Purging packages

To learn how to purge packages, please see [Package Actions](/user-interface/sidebar.html#package-actions) and [Detail Page](/user-interface/detail-area/detail-page.html)
