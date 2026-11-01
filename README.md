# SteamWorx

A custom desktop achievement management and tracking client for Steam, featuring a dark slate WPF interface.

## ⚠️ Important Information
* **Local Operation:** SteamWorx relies on official Steamworks client APIs and local VDF configuration files.
* **Server-Protected Titles:** Titles utilizing publisher server-side authorization will enforce read-only status on client-side state modifications.
* **Requirements:** The official Steam client must be installed and running in the background.

## Features
* **Modern WPF Interface:** Custom dark theme inspired by Steam's slate navy aesthetic.
* **VDF Parsing:** Automatic detection of installed Steam games and libraries.
* **Achievement Inspection:** View local schema, unlock dates, and status across owned titles.
* **Backup Management:** Local snapshotting for game stat configurations.

## System Requirements
* Windows 10/11 (64-bit)
* .NET 8.0 Desktop Runtime
* Running Steam Desktop Client

## Installation

1. Download the latest SteamWorx release from the **Releases** page.
2. Download the SteamWorx ZIP archive.
3. Extract the ZIP file to a location of your choice.
4. Make sure the Steam desktop client is installed, running, and logged in.
5. Run `SteamWorx.exe`.
6. Wait for SteamWorx to detect Steam and populate your game library.

---

## How to use

1. Make sure the Steam desktop client is running and logged in.
2. Launch SteamWorx and allow the application to load your Steam library.
3. SteamWorx scans the locally available Steam application data and displays your library.
4. Select a game to open its Achievement Manager.
5. Browse the available achievements for the selected game.
6. Select the achievement you want to modify.
7. Click **Get Achievement** to unlock the selected achievement.
8. To lock an achievement again, select an unlocked achievement and use the corresponding lock action.
9. Repeat the process for other achievements as required.

### Achievement Management

SteamWorx allows you to manage individual Steam achievements.

- **Get Achievement:** Unlocks the selected achievement.
- **Lock Achievement:** Locks the selected achievement again.

Standard MIT License and raise issue in case of bugs.
