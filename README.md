# Download

## Core
### About
Core is the modloader that manages plugins. It is required if you want to run Multiplayer or any other plugins.
### Download
[v0.11.2](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/core_0.11.2/Core.zip) | [patch notes](https://github.com/Jump-King-Modding-Platform/Releases/releases/tag/core_0.11.2) (latest)\
[v0.11.1](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/core_0.11.1/Core.zip) | [patch notes](https://github.com/Jump-King-Modding-Platform/Releases/releases/tag/core_0.11.1)\
[v0.9.1](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/core_0.9.1/Core.zip)\
[v0.9.0](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/core_0.9.0/Core.zip)\
[v0.8.3](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/core_0.8.3/Core.zip)

## Multiplayer
### About
This is the plugin that adds multiplayer support to Jump King.

**Note that it requires Core to be installed as well!**
### Download
**Requires Core 0.11.x**\
**Requires [Visual C++ Redistributable x86 for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48145)**\
[v0.3.1](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.3.1/Multiplayer.zip) | [patch notes](https://github.com/Jump-King-Modding-Platform/Releases/releases/tag/mp_0.3.1) (latest)\
[v0.3.0](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.3.0/Multiplayer.zip) | [patch notes](https://github.com/Jump-King-Modding-Platform/Releases/releases/tag/mp_0.3.0)

**Requires Core 0.9.1**\
[v0.2.1](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.2.1/Multiplayer.zip)

**Requires Core 0.9.0**\
[v0.2.0](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.2.0/Multiplayer.zip)

**Requires Core 0.8.3**\
[v0.1.7](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.7/Multiplayer.zip)\
[v0.1.6](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.6/Multiplayer.zip)\
[v0.1.5](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.5/Multiplayer.zip)\
[v0.1.4](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.4/Multiplayer.zip)\
[v0.1.3](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.3/Multiplayer.zip)\
[v0.1.2](https://github.com/Jump-King-Modding-Platform/Releases/releases/download/mp_0.1.2/Multiplayer.zip)

# Jump King Plus support
It's fully possible to have both JK+ and JKMP installed at the same time, but JK+ needs to be installed first.

If you installed JK+ after JKMP then rerun the JKMP.Patcher file in the game directory (mentioned in the instructions).

# Instructions

## How to install Core
1. Download the latest version above.
   * If your browser warns that the file is unsafe, choose the option to keep it anyway. This warning appears for files that are rarely downloaded. This will most likely be the case for new releases.
   * **IMPORTANT:** Most people have had to unblock the zip file in Windows, a small percentage so far have not. Open the location of the zip file and right click it and press Properties at the bottom. Check ```Unblock``` in the bottom right of the window and then press OK. If it does not exist then you're good. [Image](.github/media/instructions/install/unblock.png)
2. Extract the files to the game directory
   1. Right click the zip file and press ```Extract All...```
   2. Right click the game in Steam and click ```Manage > Browse local files``` [Image](.github/media/instructions/install/steam-browse-local-files.png)
   3. Copy the file path and paste it into the extraction file path. [Image](.github/media/instructions/install/copy-game-filepath.png)
   4. Click Extract and choose ```Replace the files in the destination``` when it asks to overwrite existing files. [Image](.github/media/instructions/install/overwrite-existing-files.png)
3. Open the game folder and run JKMP.Patcher. Make sure the message ```All patches applied successfully!``` is displayed. [Image](.github/media/instructions/install/run-patcher.png)

## How to install plugins
In this guide we're gonna be using the Multiplayer plugin as an example.
1. Download the latest version of the plugin.
   * If your browser warns that the file is unsafe, choose the option to keep it anyway. This warning appears for files that are rarely downloaded. This will most likely be the case for new releases. [Image](.github/media/instructions/install/dl-keep-dangerous-mp.png)
   * **IMPORTANT:** Most people have had to unblock the zip file in Windows, a small percentage so far have not. Open the location of the zip file and right click it and press Properties at the bottom. Check ```Unblock``` in the bottom right of the window and then press OK. If it does not exist then you're good.
2. (Optional) If you're installing a new version of the mod, delete the old one first in the game folder ```JKMP/Plugins/Multiplayer```.
3. Extract the files to the game directory
   1. Right click the downloaded zip file and press ```Extract all...```
   2. Right click the game in Steam and click ```Manage > Browse local files``` [Image](.github/media/instructions/install/steam-browse-local-files.png)
   3. Copy the file path and paste it into the extraction file path. [Image](.github/media/instructions/install/copy-game-filepath.png)
   4. If you get the question to overwrite existing files make sure you deleted the previous version of the plugin first.

# Troubleshooting
It might help to enable the console to troubleshoot if the game doesn't start or if it's acting weird. To do this add ```--console``` to the game's launch arguments. [Image](.github/media/instructions/troubleshooting/steam-console-launch-arguments.png)

<details>
<summary>
Expand me to find some common errors that may be thrown at you
</summary>

```System.NotSupportedException: An attempt was made to load an assembly from a network location...```\
  Alternatively: The game closes on startup without anything showing up.

To fix this you have to unblock the zip file in Windows before extracting it to the game folder. There's instructions for this above in the substeps of step 1. When extracting the second time make sure you overwrite all existing files.

```Failed to connect to matchmaking server: Your version is outdated```

To fix this you have to update your multiplayer version.
</details>
