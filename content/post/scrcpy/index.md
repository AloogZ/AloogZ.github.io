+++
author = "Vighnesh Nilajakar"
title = "Scrcpy"
date = "2023-06-04"
description = "Screen Mirroring made easier !"
tags = [
    "CLI",
	"Screen Mirroring"]
categories = [
    "Applications"]
image = "scrcpy_logo.png"
+++

## Introduction
Scrcpy, derived from "Screen Copy," is an impressive application that offers mirroring and control capabilities for Android devices via USB or over a network connection. It is a versatile, open-source, and free tool that works on multiple platforms. To use Scrcpy, your Android device should be running at least Android 5.0, and USB or ADB debugging needs to be enabled. Some users may require additional settings to control the mouse and keyboard.

![SCRCPY](https://raw.githubusercontent.com/AloogZ/AloogZ.github.io/main/content/post/scrcpy/scrcpy_poster.gif)
## Installation
To install Scrcpy, you can refer to its [GitHub page](https://github.com/Genymobile/scrcpy#get-the-app) for detailed installation and usage instructions. If you prefer using the Chocolatey package manager, you can install Scrcpy by running the following commands:

`choco install adb`
`choco install scrcpy`


## Features
Scrcpy offers a range of powerful features that enhance your Android device mirroring and control experience. Let's explore some of its notable features :-

* ### Recording
	Scrcpy provides a convenient recording feature that allows you to capture your Android screen. This is particularly useful for recording games without impacting device performance. The video is recorded on your computer, reducing device buffering. Learn more about recording with Scrcpy [here](https://github.com/Genymobile/scrcpy#recording).

* ### Connectivity
	Scrcpy leverages the power of ADB (Android Debug Bridge) to establish connections with Android devices. It enables screen mirroring over a network connection using TCP/IP. For Android 11+ devices, wireless debugging is supported. If wireless connections are unstable, you can optimize them by adjusting the bit rate and resolution. Scrcpy also allows connecting your device to remote devices through tunneling. Read more about Scrcpy's connectivity options [here](https://github.com/Genymobile/scrcpy#connection).

* ### Window Configuration
	With Scrcpy, you can customize how mirrored windows are displayed. You have control over the window title, size, borders, device rotation, touch interactions, stay-awake settings, and fullscreen mode. It also supports input control synchronization between your Android device and PC, making it convenient for editing documents and supporting gestures like pinch to zoom. Scrcpy can simulate your PC's keyboard and mouse as if they were physically connected to your Android device. Learn more about window configuration [here](https://github.com/Genymobile/scrcpy#window-configuration).

* ### Input Control
	Scrcpy provides flexible input control options for interacting with your Android device from your computer. It supports various control modes, including OTG mode where you can simulate your PC's mouse and keyboard connected to the Android device. OTG mode is especially useful for gaming on Android, as supported games often have in-game keyboard controls similar to gaming on a PC. Check out this [video](https://github.com/Genymobile/scrcpy#input-control) demonstrating Minecraft gameplay using Scrcpy's OTG mode. While in OTG mode, screen mirroring is not supported. Learn more about input controls [here](https://github.com/Genymobile/scrcpy#input-control).

	<iframe title="vimeo-player" src="https://player.vimeo.com/video/782246242?h=4d50e72202" width="100%" height="100%" frameborder="0" allowfullscreen></iframe>

* ### File Drop
	Scrcpy supports a convenient file drop feature that allows you to install applications on your Android device by simply dropping APK files from your computer onto the screen mirroring window. There won't be any visual feedback on the Android device or the mirrored screen, but a log will be printed in the terminal. You can also send files by dragging them onto the mirrored screen window. Learn more about file drop [here](https://github.com/Genymobile/scrcpy#file-drop).

* ### Keyboard Shortcuts
	In addition to mouse and touch controls, Scrcpy offers several keyboard shortcuts for quick access to various functions. For example, you can switch between fullscreen and windowed mode, rotate the device, toggle FPS counter, copy the device clipboard to the computer, and more. Check out the full list of keyboard shortcuts [here](https://github.com/Genymobile/scrcpy#keyboard-shortcuts).

## Conclusion
Scrcpy is a powerful tool that simplifies mirroring and controlling Android devices from your computer. Its extensive features, including screen recording, connectivity options, window configuration, input control, file drop, and keyboard shortcuts, make it a versatile solution for developers, gamers, and anyone who needs to interact with their Android device on a larger screen. Give Scrcpy a try and experience the convenience and flexibility it offers!
