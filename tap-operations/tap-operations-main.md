---
layout: default
title: Tap Operations
---

Taps are sources of additional packages not found in base Homebrew. If you can't find a package, chances are there's a tap that contains that package.

Each tap name starts with the name of the project or delevoper maintaining the tap, followed by a slash, and ends with the repository the tap is contained within.

Here are some examples of tap names:
* **homebrew/core**: [project name: **homebrew**]/[repository name: **core**]
* **elastic/tap**: [project name: **elastic**]/[repository name: **tap**]

For all intents and purposes, you can think of the entire tap name as a singular unit; after all, when adding a tap, Cork checks if the tap name fulfills the above requirements automatically, and will not let you add a tap with an invalid name.

## Adding Taps

To add a tap:
<ol>
    <li><p>Click the <img src="./Assets/Tap Icon.jpg" class="inline"> button in the toolbar. A dialog with a text field will open.</p></li>
    <li><p>Write in the tap name in and press <b>Add</b>.</p></li>
    <li>Wait until Cork adds the tap.</li>
</ol>

## Inspecting Taps

You can see info about a tap, such as the packages contained within, whether the tap has been audited for malicious packages, and other, by clicking it in the Taps section of the [Sidebar](/user-interface/sidebar.html). A [Detail Page](/user-interface/detail-area/detail-page.html#tap-details) for the tap will open.

## Removing Taps

To remove a tap:
* Right-click a tap in the [Sidebar](/user-interface/sidebar.html), then press **Remove [tap name]**
* Open the tap's [Detail Page](/user-interface/detail-area/detail-page.html), then press **Remove [tap name]** at the bottom of the page.
