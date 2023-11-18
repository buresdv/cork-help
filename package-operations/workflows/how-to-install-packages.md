---
layout: default
title: How to Install a Package
---

You can start installing a package in three ways:
- <p>Click <img src="/package-operations/workflows/Assets/Install Button.jpg" class="inline"> in the <a href="/user-interface/toolbar.html">toolbar</a></p>
- Press `⌘ + N`
- Select **Install Packages** in the Menu Bar, in **Packages → Install Packages** 

No matter which one you choose, a dialog with the title "Install packages" will appear.

## Installation Steps

Now, we will go over every step of the installation process.

<separator></separator>

![Install Start](./Assets/Install%20Start.png)
### Search for Packages

If you enabled [Discoverability](./discoverability.html), you will see a list of the most popular packages, depending on how you [configured](/settings/sections/discoverability.html) this feature. You can select a package from this list and click **Install** to immediately start installing that package.

If you have not enabled Discoverability, you will see a text field. Write the name of the package you'd like to install into this field, and either press `Return ↩` on your keyboard, or click **Search**.

<separator></separator>

![Search Results](./Assets/Search%20Results.png)
### Choose the Right Package

After a few seconds, you will see a list of the best matches. The way this list will look depends on how you [set up](/getting-started/first-steps/main.html) Cork, and how you [changed the various settings](/settings/main.html).

In any case, you will see a list of packages. The list is divided into [Formulae and Casks](/getting-started/main.html#cork-terminology), with each section collapsible by clicking **Hide** on the right side of its section header.

When you find the package you want to install, click on it to select its row, then click **Install**.

If you have not found the package you were looking for, you can search for a different keyword by using the search field at the top of the dialog. Write in your new search query, and either pres `Return ↩` on your keyboard, or click **Search**.

<separator></separator>

![Install Process Running](./Assets/Install%20Process%20Running.png)
### Let the Installation Run

This step of the process is entirely automated. You will see the description of the current step of the installation process at the top of the dialog, with a progress bar under it that shows you the overall progress of the installation.

If you have enabled the [showing of real-time outputs of operations](/settings/sections/packages.html), you will also see the real-time output of the operation above the progress bar. To expand it, click **Show details**.

<separator></separator>

![Install Process Successful](./Assets/Install%20Process%20Successful.png)
### Finish the Installation

At the end of the install process, you will see a dialog that confirms that the installation was successful.

## Troubleshooting

Sometimes, installations might not go as planned.

### Elevated Permissions Required

![Eleated permissions required dialog](./Assets/Additional%20Permissions.png)

Some packages might require elevated permissions. In such cases, a dialog pictured above will appear. To finish installing such package, follow the instructions in the dialog.

### Dialog Goes Blank

This is a known issue caused by Apple. As of now, there is not fix apart from clicking on the Cork icon in the Dock while holding `Option ⌥`, and clicking **Force Quit**.

### Installation failed

For reasons such as broken Homebrew installations, unstable internet, and other rare situations, the installation process might fail, in which case you will see a failure dialog. If this happens, restart your Mac and try again.