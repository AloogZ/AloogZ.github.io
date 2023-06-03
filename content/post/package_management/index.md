+++
author = "Vighnesh Nilajakar"
title = "Package Management"
date = "2023-05-30"
description = "Package Management in Windows !"
tags = [
    "CLI",
	"Package Management"]
categories = [
    "Applications"]
image = "GTA6_poster.webp"
+++

# Package Management

## Introduction

Installing Applications in Windows isn't Secure. We either download executable files from some Websites or from The Microsoft Store where many Applications are Paid or Unavailable. Also, Installing Executables from some Random Websites, Makes updating them a pain in the ass and nor these Executable Files Verified. Also with The Microsoft Store, You don't get the entire fleet of Applications to Install. So, What is the Solution?

## Package Managers

Package Managers are Primarily Software to Manage your Applications, Just like The Proprietary Microsoft Store in Windows. On the other hand, Linux uses Package Managers like apt, yum, DNF, Pacman, etc. But, Following the FOSS Ideology, We will be using a Free and Open Source Package Manager for Windows. Which can Install, Uninstall or Update Applications for free.  
These Package Managers basically, Have a Huge Repository of Executable Files and, When we ask our Package Manager to Install an Application, They Download the Executable File and Install it. Similarly, They can Update and Uninstall the Packages too.

### Winget

Now, Microsoft has created an Open Source Tool that is a Replacement for The Microsoft Store which is also known as [Winget (Windows Package Manager)](https://learn.microsoft.com/en-us/windows/package-manager/), Microsoft Store has a Huge Repository of Applications and this Utility helps a lot in managing packages in Windows. Kudos to Microsoft for that !  
Its Installation Process is really easy, and Here is its [Installation Guide](https://learn.microsoft.com/en-us/windows/package-manager/winget/#install-winget) and, its [Usage Guide](https://learn.microsoft.com/en-us/windows/package-manager/winget/#use-winget) by Microsoft. You can also use [winget.run](https://winget.run/) to Find Packages and their Install Commands. Here is a little GIF of the Installation Process of yt-dlp with winget.

![Installing yt-dlp with winget]()

### Chocolatey

Now, Some Applications aren't supported by Winget. So, We can use [Chocolatey](https://chocolatey.org/) which is similar to Winget but supports more open-source packages. You can visit this website's [Install Page](https://docs.chocolatey.org/en-us/choco/setup#installing-chocolatey) and [Usage Page](https://docs.chocolatey.org/en-us/choco/commands/) for choco(CLI). Also, there is a GUI for Choco too, which will be similar to the Microsoft Store. Here is its [Installation Guide](https://docs.chocolatey.org/en-us/chocolatey-gui/setup/installation). They also have a [Find Packages](https://community.chocolatey.org/packages) Page, which can be used to find Applications and their details. Here is Another GIF of Uninstalling sharex with Choco

![Uninstalling ShareX with choco]()

### Scoop

[Scoop](https://scoop.sh/) is another Package Manager to scoop out Packages, It just Increases the variety of Packages you can Install. It stores Application in a Different Directory, In order to Sandbox them. It is a great Package Manager to Increase the Repository of Applications to Install. Anyways you can visit its [Website](https://scoop.sh/), It has pretty easy and clear instructions to [Install](https://scoop.sh/#/) it. Also, you can browse Installable Applications on [this page](https://scoop.sh/#/apps?s=0&d=1&o=true). Here is a GIF of Updating all Applications with scoop.

![Updating all with Scoop]()

## Conclusion

Again, Installing and Using these Package Managers is really easy. So, I suggest you use these Package Managers. There are many more Package Managers like Scoop, Ninite, and Yarn. Personally, I use Chocolatey and Winget. So, I don't know about them, but you can Explore more Package Managers according to your needs.