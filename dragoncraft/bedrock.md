---
title: Bedrock
description: 
published: true
date: 2021-02-23T16:19:04.084Z
tags: 
editor: markdown
dateCreated: 2020-11-10T17:07:01.709Z
---

# Bedrock Edition
Bedrock Edition refers to the multi-platform family of editions of Minecraft, which includes all currently supported editions except Java Edition. Previously, before the Better Together update, Bedrock Edition was also referred to as "Pocket Edition", "MCPE", or "Windows 10 Edition".

> This edition of Minecraft officially supports mobile devices and virtual reality headsets.
{.is-success}

To join the Dragon Craft server for Minecraft: Bedrock Edition, use the following address: `craft.dragonprojects.net`.

## macOS and Linux support
Though Minecraft: Java Edition is the only version of Minecraft that officially supports macOS and Linux, using a community-provided tool called "Minecraft Bedrock Launcher", you can run Bedrock Edition on these platforms as well.

> You cannot use the macOS version of Minecraft: Education Edition to play with Minecraft: Bedrock Edition players, despite both games using the same engine.
{.is-danger}

macOS users should download the application [here](https://mrarm.io/r/mcpelauncher-osx) and drag it to their Applications folder. Linux users are advised to install Minecraft Bedrock Launcher using Flatpak.

1. Install Flatpak, a package manager that will help you install and keep Minecraft Bedrock Launcher up-to-date. Instructions on how to do so can be found [here](https://www.flatpak.org/setup/).
2. Setup Flathub, the repository you will install Minecraft Bedrock Launcher from, by running the command below in your Terminal.
```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
3. Now, install Minecraft Bedrock Launcher from Flathub with the Flatpak package manager.
```bash
flatpak install flathub io.mrarm.mcpelauncher
```
4. After installation, a shortcut which launches Minecraft Bedrock Launcher should appear on your desktop or in your launcher, depending on your desktop environment. It is also possible to launch the application using the terminal.
```bash
flatpak run io.mrarm.mcpelauncher
```

After installation, open Minecraft Bedrock Launcher. In order to get the game to work, the launcher will need you to provide the Android (APK) version of Minecraft: Bedrock Edition. You will be asked to login with your Google account for this reason. Make sure you have purchased [Minecraft on Google Play](https://play.google.com/store/apps/details?id=com.mojang.minecraftpe). Alternatively, instead of logging in, you can provide an APK file of the game.

You will now be able to run Minecraft: Bedrock Edition on macOS and Linux. For more information, take a look at the [Minecraft Bedrock Launcher documentation](https://mcpelauncher.readthedocs.io).

## Third-Party Servers on Consoles
By default, Minecraft: Bedrock Edition on most gaming consoles will only allow you to connect to servers that have been approved by Microsoft/Mojang. By utilising [BedrockConnect](https://github.com/Pugmatt/BedrockConnect), you can circumvent this and join third-party servers, like Dragon Craft, on your gaming console. To get started, go to the network settings of your device and change your primary DNS server to `104.238.130.180`, while setting the secondary DNS server to `1.1.1.1`. Afterwards, open up Minecraft, attempt to join any of the featured servers and you will be brought to a menu where you will be able to add third-party servers, for example, Dragon Craft.

## Java Compatibility
Officially, Minecraft: Bedrock Edition does not support multiplayer with Minecraft: Java Edition servers. However, an unofficial tool called Geyser allows Bedrock Edition players to join Java Edition servers by translating all the incoming and outgoing packets. This can be used to join the Java Edition Dragon Craft server, for example.

To get information on how to setup GeyserMC, [visit their wiki](https://github.com/GeyserMC/Geyser/wiki#Setup). You will need to use the Standalone Setup for Dragon Craft.

Alternatively, for something less involved, you might be interested in using BedrockConnect's compatibility mode for Java Edition servers.