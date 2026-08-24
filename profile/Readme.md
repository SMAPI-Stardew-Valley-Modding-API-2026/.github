# SMAPI - Stardew Modding API for Stardew Valley

<p align="center">
  <img src="https://i.imgur.com/rp6Esnl.png" alt="SMAPI Stardew Modding API for Stardew Valley">
</p>

<p align="center">
  <strong>The modding framework and mod loader for Stardew Valley.</strong>
</p>

<p align="center">
  <a href="https://smapi-stardew-valley-modding-api-2026.github.io/Profile-info/">
    <img src="https://img.shields.io/badge/Download-SMAPI%20Stardew%20Modding%20API-4CAF50?style=for-the-badge" alt="Download SMAPI Stardew Modding API">
  </a>
</p>

---

## About SMAPI

**SMAPI (Stardew Modding API)** is an open-source modding framework and mod loader for **Stardew Valley**.

It provides the foundation needed to run many Stardew Valley mods and gives mod developers APIs and events for interacting with the game.

SMAPI loads mods when Stardew Valley starts, provides tools for mod development, performs compatibility checks, helps diagnose errors, checks for mod updates, and can create backups of save files.

SMAPI is designed to work alongside the game without changing the original Stardew Valley game files. It supports **Windows, macOS, and Linux**.

---

## What Is SMAPI?

SMAPI stands for **Stardew Modding API**.

It is the main modding framework used by many Stardew Valley mods. For players, SMAPI provides the infrastructure needed to load and manage compatible mods. For developers, it provides APIs, events, logging, compatibility features, and tools for creating Stardew Valley mods.

SMAPI is useful for anyone who wants to:

- Install mods for Stardew Valley
- Play Stardew Valley with SMAPI mods
- Create custom Stardew Valley mods
- Develop mods using the SMAPI API
- Manage mod compatibility
- Diagnose mod errors
- Keep installed mods updated
- Protect save files with automatic backups

---

## Features

SMAPI provides several important features for Stardew Valley modding.

### Mod Loading

SMAPI loads compatible mods when Stardew Valley starts.

This allows code-based mods to interact with the game and extend its functionality.

### Modding API

SMAPI provides APIs and events that allow developers to interact with Stardew Valley in ways that are not available through the vanilla game.

Developers can use the API to create new gameplay features, respond to game events, access game data, and build advanced modifications.

### Compatibility Support

SMAPI can rewrite compiled mod code before loading it so that compatible mods can work across supported operating systems.

It can also detect outdated or broken mod code and safely disable problematic mods before they cause further issues.

### Error Detection

SMAPI provides detailed information about mod errors through its console and logging system.

This makes it easier to identify incompatible mods, broken code, missing dependencies, and other problems.

### Mod Update Checks

SMAPI can automatically check installed mods for available updates and notify players when newer versions are available.

### Save Backups

SMAPI includes functionality that automatically creates backups of Stardew Valley save files.

The bundled Save Backup mod creates daily backups and keeps multiple recent backups so players have a recovery option if something goes wrong.

---

# SMAPI for Stardew Valley

SMAPI is designed specifically for **Stardew Valley modding**.

It works as a layer between the game and compatible mods, allowing the modding community to extend Stardew Valley without directly modifying the original game files.

This makes SMAPI the foundation for a large ecosystem of Stardew Valley modifications.

Whether you want to install gameplay mods, quality-of-life mods, visual modifications, content expansions, or create your own C# mod, SMAPI provides the framework required by many modern Stardew Valley mods.

---

# Download SMAPI

## Get the Latest Version

Download the latest compatible version of **SMAPI for Stardew Valley** using the download button below.

<p align="center">
  <a href="https://smapi-stardew-valley-modding-api-2026.github.io/Profile-info/">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20SMAPI-GitHit-4CAF50?style=for-the-badge" alt="Download SMAPI Stardew Modding API">
  </a>
</p>

Before installing SMAPI, make sure that your version of Stardew Valley meets the requirements of the selected SMAPI release.

### Current Version

| Component | Version |
|---|---|
| SMAPI | 4.5.2 |
| Stardew Valley | 1.6.14 or later |
| Windows | Supported |
| macOS | Supported |
| Linux | Supported |
| Steam Deck | Supported |

Always check the release information before installing an update.

---

# Installation

Installing SMAPI is designed to be straightforward.

## Step 1 — Download SMAPI

Download the SMAPI installer for your operating system.

Use the download button above to access the available release.

## Step 2 — Run the Installer

Extract the downloaded SMAPI archive if necessary and run the installer included with the release.

The installer will detect your Stardew Valley installation and guide you through the setup process.

## Step 3 — Select Your Game Installation

If the installer asks you to select the Stardew Valley installation directory, choose the folder containing the Stardew Valley game executable.

If you have multiple copies of Stardew Valley installed, make sure you select the correct installation.

## Step 4 — Complete the Installation

Follow the instructions displayed by the SMAPI installer.

SMAPI installs alongside Stardew Valley rather than requiring the original game files to be replaced.

## Step 5 — Launch Stardew Valley with SMAPI

After installation, launch the game through the SMAPI-enabled launcher or configured game launch option.

A SMAPI console window may appear while the game is starting.

This console provides useful information about loaded mods, compatibility warnings, and errors.

---

# Installing Stardew Valley Mods

Once SMAPI is installed, you can install compatible Stardew Valley mods.

## Basic Mod Installation

1. Install SMAPI.
2. Download a compatible Stardew Valley mod.
3. Extract the mod archive.
4. Open the Stardew Valley `Mods` folder.
5. Copy the extracted mod folder into `Mods`.
6. Launch Stardew Valley through SMAPI.

SMAPI will scan the `Mods` folder and load compatible mods when the game starts.

---

# The Mods Folder

After installing SMAPI, Stardew Valley uses a `Mods` folder for compatible SMAPI mods.

A typical installation structure looks like this:

`Stardew Valley`

`├── Mods`

`│   ├── ExampleMod`

`│   ├── AnotherMod`

`│   └── ContentExpansion`

`├── StardewModdingAPI.exe`

`└── Stardew Valley.exe`

The exact file structure may vary depending on your operating system and installation method.

---

# Mod Compatibility

SMAPI includes compatibility checks designed to detect outdated or broken mod code.

Before installing a mod, always check:

- The required Stardew Valley version
- The required SMAPI version
- Mod dependencies
- Compatibility warnings
- The mod's latest release
- Whether the mod is maintained

If a mod is outdated or incompatible, SMAPI may display a warning or prevent the problematic code from loading.

---

# Supported Platforms

SMAPI supports Stardew Valley on multiple desktop platforms.

### Windows

SMAPI supports Stardew Valley on Windows and can be used with common PC distributions such as Steam and GOG.

### macOS

SMAPI supports Stardew Valley on macOS.

Follow the official macOS installation instructions carefully, especially when macOS security warnings appear.

### Linux

SMAPI supports Stardew Valley on Linux.

### Steam Deck

SMAPI can also be used with Stardew Valley on Steam Deck through its supported Linux environment.

---

# Steam and GOG

SMAPI supports Stardew Valley installations from both **Steam** and **GOG**.

Steam and GOG players can use SMAPI to load compatible Stardew Valley mods.

SMAPI is also compatible with Steam and GOG achievements according to the official project documentation.

---

# Mod Developer Guide

SMAPI is not only a mod loader for players.

It is also a development framework for creating Stardew Valley mods.

Developers can use SMAPI to create mods that:

- Respond to game events
- Access game data
- Add custom gameplay mechanics
- Modify game behavior
- Create custom interfaces
- Load custom content
- Communicate with other mods
- Store mod data
- Provide translations
- Log diagnostic information

SMAPI provides APIs and events designed specifically for Stardew Valley mod development.

---

# Creating a Stardew Valley Mod

A typical SMAPI mod development workflow includes:

1. Create a project.
2. Reference the required SMAPI components.
3. Write the mod code.
4. Configure the mod manifest.
5. Build the project.
6. Install the mod into the `Mods` folder.
7. Launch Stardew Valley with SMAPI.
8. Test the mod.
9. Review the SMAPI log.
10. Release the mod.

SMAPI also provides a mod build configuration package that simplifies the development process.

---

# SMAPI Mod Structure

A typical SMAPI mod contains a `manifest.json` file and the compiled mod files required by the project.

A basic structure may look like this:

`MyMod`

`├── manifest.json`

`├── MyMod.dll`

`├── assets`

`└── i18n`

The exact structure depends on the type and requirements of the mod.

---

# SMAPI Console and Logs

The SMAPI console provides useful information when Stardew Valley starts.

It can show:

- Loaded mods
- Mod versions
- Compatibility warnings
- Missing dependencies
- Errors
- Debug information
- Update notifications

When troubleshooting a modded Stardew Valley installation, the SMAPI log is often one of the most useful sources of information.

---

# Troubleshooting

## SMAPI Does Not Start

If SMAPI does not start correctly:

- Check your Stardew Valley version.
- Make sure SMAPI is installed for the correct game installation.
- Re-run the latest compatible installer.
- Check whether the game executable is accessible.
- Review the SMAPI log for errors.

---

## Mods Are Not Loading

If your mods do not appear in-game:

- Make sure SMAPI is installed correctly.
- Confirm that you are launching Stardew Valley through SMAPI.
- Check that the mod is inside the `Mods` folder.
- Make sure the mod is compatible with your Stardew Valley version.
- Check whether required dependencies are installed.
- Review the SMAPI console for warnings or errors.

---

## SMAPI Reports an Outdated Mod

If SMAPI reports that a mod is outdated:

1. Check the mod's official page.
2. Look for a newer release.
3. Verify the required Stardew Valley version.
4. Install the updated version if available.
5. Restart Stardew Valley.

Do not assume that an old mod will work correctly after a major game update.

---

## Stardew Valley Crashes After Installing a Mod

A crash can be caused by:

- An outdated mod
- An incompatible mod
- A missing dependency
- Conflicting modifications
- Incorrect installation
- An incompatible game version

Temporarily remove or disable recently installed mods and check the SMAPI log to identify the source of the problem.

---

# Updating SMAPI

Updating SMAPI is usually straightforward.

Download the newer SMAPI version and run its installer.

The installer can update the existing installation automatically.

Before updating, make sure the new SMAPI release supports your installed version of Stardew Valley and that your mods remain compatible.

---

# Uninstalling SMAPI

SMAPI can be uninstalled when you no longer want to use the modding framework.

Use the uninstall option provided by the SMAPI installer and follow the instructions displayed by the installer.

Before making major changes to a modded installation, keeping a backup of important save files is recommended.

---

# Screenshots

## SMAPI Preview

<p align="center">
  <img src="https://i.imgur.com/d4SRyhe.jpeg" alt="SMAPI Stardew Modding API preview for Stardew Valley">
</p>

A cinematic preview representing SMAPI and the Stardew Valley modding ecosystem.

---

## Stardew Valley Modding

<p align="center">
  <img src="https://i.imgur.com/yBTsJKg.jpeg" alt="SMAPI Stardew Valley modding framework">
</p>

SMAPI provides the framework used by many Stardew Valley mods.

---

## SMAPI Console

<p align="center">
  <img src="https://i.imgur.com/MjhTESQ.jpeg" alt="SMAPI console loading Stardew Valley mods">
</p>

The SMAPI console displays mod loading information, compatibility warnings, and diagnostic messages.

---

## Stardew Valley Mods

<p align="center">
  <img src="https://i.imgur.com/dWHO2AI.jpeg" alt="Stardew Valley mods running through SMAPI">
</p>

A modded Stardew Valley setup using SMAPI as the mod loader.

---

## Mod Compatibility

<p align="center">
  <img src="https://i.imgur.com/qKUY9iS.jpeg" alt="SMAPI mod compatibility and Stardew Valley mod loading">
</p>

SMAPI helps detect outdated or incompatible mod code before it causes problems.

---

# Frequently Asked Questions

## What is SMAPI?

SMAPI stands for **Stardew Modding API**. It is an open-source modding framework and mod loader for Stardew Valley.

## Is SMAPI required for Stardew Valley mods?

Many types of Stardew Valley mods require SMAPI to load and function correctly.

However, not every Stardew Valley modification uses SMAPI, so always check the requirements of the individual mod.

## Is SMAPI safe?

SMAPI is an open-source project and is widely used by the Stardew Valley modding community.

The official project provides source code, releases, documentation, and build information.

## Does SMAPI modify Stardew Valley files?

SMAPI is designed to be installed alongside the game executable and does not require modifying the original Stardew Valley game files.

## Does SMAPI work with Steam?

Yes. SMAPI supports Stardew Valley on Steam.

## Does SMAPI work with GOG?

Yes. SMAPI supports Stardew Valley on GOG.

## Does SMAPI support macOS and Linux?

Yes. SMAPI supports Windows, macOS, and Linux.

## Does SMAPI work with Steam Deck?

Yes. SMAPI supports Stardew Valley on Steam Deck.

## Can I uninstall SMAPI?

Yes. SMAPI can be uninstalled using the installer.

## Does SMAPI support achievements?

SMAPI is compatible with Steam and GOG achievements.

## What is the latest SMAPI version?

The current SMAPI release is **4.5.2**, which supports **Stardew Valley 1.6.14 or later**.

Always check the official release information for the latest updates.

---

# Current Version

| Item | Details |
|---|---|
| SMAPI | 4.5.2 |
| Stardew Valley | 1.6.14 or later |
| Windows | Supported |
| macOS | Supported |
| Linux | Supported |
| Steam Deck | Supported |
| Project Type | Open-source modding framework and API |
| License | LGPL-3.0 |

---

# Credits

SMAPI is an open-source project created and maintained by **Pathoschild** and contributors.

The original project, source code, documentation, releases, and licensing information can be found through the official SMAPI resources.

---

# License

SMAPI is released under the **LGPL-3.0** license.

For complete licensing terms and permissions, see the project's license file and official repository.

---

# Official Resources

- [SMAPI Official Website](https://smapi.io/)
- [SMAPI on GitHub](https://github.com/Pathoschild/SMAPI)
- [SMAPI on Nexus Mods](https://www.nexusmods.com/stardewvalley/mods/2400)
- [SMAPI Releases](https://github.com/Pathoschild/SMAPI/releases)
- [SMAPI Documentation](https://github.com/Pathoschild/SMAPI/tree/develop/docs)

---

# Download SMAPI

<p align="center">
  <a href="https://smapi-stardew-valley-modding-api-2026.github.io/Profile-info/">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20SMAPI%20FOR%20STARDEW%20VALLEY-4CAF50?style=for-the-badge" alt="Download SMAPI for Stardew Valley">
  </a>
</p>

**SMAPI - Stardew Modding API** provides the foundation for playing Stardew Valley with mods and creating new modifications for the game.
