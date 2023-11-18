---
layout: default
title: Package Operations
---

You can add, update and remove packages easily.

## Installing Packages

To add a new package, you can use one of three workflows:

- Use the **Install** button in the [Toolbar](/user-interface/toolbar.html)
- Press `⌘ + N`
- Select **Install Packages** in the Menu Bar, in **Packages → Install Packages** 

To learn more about installing packages, see [How to Install Packages](/package-operations/workflows/how-to-install-packages.html)

## Keeping Packages Up to Date

Cork offers two main ways of updating packages: 

- **Complete update**, which updates all your packages, unless they are [pinned](/package-operations/advanced/pin.html)
- **Partial update**, which updates only the packages you select

### Complete Update

To manually update all packages, you can use one of two workflows:

- Use the **Update** button in the [Toolbar.](/user-interface/toolbar.html)
- Press `⌘ + R`.
- Select **Update Packages** in the Menu Bar, in **Packages → Update Packages**.

### Partial Update

You can select which updates you'd like to update on the [Status Page](/user-interface/detail-area/status-page.html):

1. Expand the list of outdated packages by clicking the **Outdated packages** dropdown.
2. Select the packages you'd like to update. You can use **Deselect All** and **Select All** to quickly change the state of all outdated packages.
3. Click **Update [number] packages**

After the process finishes, the selected packages will be updated.

## Uninstalling Packages

To uninstall a package, you can either:

- Right-click it in the [Sidebar](/user-interface/sidebar.html) and click **Uninstall [package name]**.
- Open the package's [Detail Page](/user-interface/detail-area/detail-page.html) and click **Uninstall [package name]** at the bottom of the page.

There's a more complete, but dangerous, was to uninstall packages, called [Purging](/package-operations/advanced/purging.html). Keep in mind that purging packages is inherently more dangerous and might break your Homebrew installation if not used properly.
