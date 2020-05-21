---
date: 2020-05-21 18:19:07 +0530
layout: post
title: Microsoft releases Terminal 1.0 and Windows Package Manager
subtitle: Microsoft had announced Windows Terminal.
description: Microsoft had announced Windows Terminal.
image: https://www.xda-developers.com/files/2020/05/Windows-Terminal-810x298_c.jpg
image_source: XDA
image_source_url: https://xda-developers.com
category: tech-knowledge
tags:
  - Windows Terminal
  - linux gui
  - wsl 2
author: Sudharshan TK
source_name: XDA
source_url: https://www.xda-developers.com/microsoft-releases-windows-terminal-1-0-package-manager-announces-linux-gui-app-support-gpu-acceleration-subsystem-linux-wsl-2/
paginate: true
---
Microsoft holds a conference event every year for software engineers and web developers. Called Build, or //build/, the event is a conference for developers that primarily work on Windows, Microsoft Azure, and other technologies. While Microsoft holds an event on the ground every year, as they have in the past years, but because of COVID-19, Build 2020 is an online-only announcement. On the occasion, Microsoft has announced a plethora of new features, such as Windows Terminal 1.0, Windows Package Manager, Windows Subsystem for Linux 2, all of which will be useful to a lot of developers in some form or the other.

#### Windows Terminal 1.0
During the last year’s Build 2019 developer conference, Microsoft had announced Windows Terminal. This is exactly what it sounds like — a new terminal app from Microsoft.

<iframe width="806" height="453" src="https://www.youtube.com/embed/8gw0rXPMMPE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Some of the highlights of the app are the inclusion of GPU-accelerated text rendering, theming support, tabs, tear-away windows, shortcuts, full Unicode support, and more. The eventual goal of Windows Terminal is to be a good replacement to other command-line apps like PowerShell and Command Prompt.

Windows Terminal was released as a preview at Build 2019, and now, at Build 2020, the app has graduated into its full release in the form of Windows Terminal 1.0.
Windows Terminal 1.0 can be downloaded from the Microsoft Store or from GitHub. The app will be updated on a monthly basis starting from July 2020. But if you want to try out the latest features before they make their way to the stable branch, you can check out the preview channel on Microsoft Store and GitHub.

**Key features of Windows Terminal 1.0 as mentioned in Microsoft’s documentation:**

1. Multiple profiles supporting a variety of command-line applications
2. Customized color schemes and configurations
3. Custom key bindings
4. Unicode and UTF-8 character support
5. GPU accelerated text rendering
6. Background image support
7. Support for command-line arguments

Microsoft Windows Package Manager
If you are familiar with GNU/Linux distributions, you are very likely familiar with command-line package managers. To put it crudely, a package manager manages the process of installing, configuring, and uninstalling packages (or apps) on your computer. A command-line package manager does all of these tasks from the command line. Microsoft has never officially offered a command-line package manager, but that is now changing with the Windows Package Manager.

Windows has had a few popular third-party command-line package managers, like Chocolatey — but these are unofficial and not from Microsoft themselves. Unlike an app store like the Windows Store, a package manager supports installing apps from multiple sources, which makes it easy to set up different development environments with fewer friction points.

Windows Package Manager is now available in preview form. What’s even more exciting about this is the fact that it is open source.

Windows Package Manager offers the following features, when preceded with the winget command:

1. install – Installs the given application
2. show – Shows info about an application
3. source – Manage sources of applications
4. search – Find and show basic info of apps
5. hash – Helper to hash installer files
6. validate – Validates a manifest file
7. –help – Provides command line help
8. –info – Provides addition data, helpful for troubleshooting
9. –version – Provides the version of the client

To explain, if you use “winget install“, you’ll see all the command-line options to interface with Windows Package Manager. For example, if you type “winget install terminal” you’ll install the new Windows Terminal software. Windows Package Manager is pre-configured to point to the Microsoft community repository and you can search for available packages using “winget search” and display information using “winget show“. You’ll be able to add third-party repositories with “winget source” as well.

The command-line client is distributed within the App Installer package that is pre-installed on Windows. However, the client will not be made generally available during the Preview period, so you must either install a Windows 10 Insider build or sign up for the preview flight ring to receive automatic updates. Further, if you do not mind foregoing the automatic updates, you can also manually install it on any Windows 10 version since the Fall Creators Update (1709). When Windows Package Manager reaches version 1.0, it will be delivered with the Desktop App Installer.

**Windows Subsystem for Linux 2 / WSL 2 **

At Build 2019, Microsoft had announced Windows Subsystem for Linux 2, which ships a full Linux kernel, allowing you to run Linux commands and apps. For instance, you can even go ahead and compile LineageOS using WSL on Windows.

**Now, Microsoft has announced multiple major changes to the WSL:**

1. Added support for graphics processing unit (GPU) compute workflows 2. allows Linux tools to leverage GPUs to enable hardware acceleration for many development scenarios, such as parallel computation and training machine learning (ML) and artificial intelligence (AI) models.
3. Support for Linux graphical user interface (GUI) apps will enable you to open a WSL instance and run a Linux GUI app directly without the need for a third-party X server. This will help you to run your favorite apps in a Linux environment such as an integrated development environment (IDE).

WSL will soon support a simplified install experience by running the command ‘wsl.exe – install,’ which will make it easier than ever to start using Linux apps on Windows.

With these upcoming changes to WSL 2, users no longer need to run an X server to use Linux apps with GUIs. Linux apps will also now run much more seamlessly on Windows. As Mishaal points out, this might just be the tipping point for the “year of the Linux desktop” meme to finally come true, and it’s ironic that it is Microsoft that is bringing this around.