# Half-Life 2 Adaptive Music Mod
Version : 0.1.0-alpha

## How to setup the prerequisites
1. Make sure you download and install an Half-Life 2 game and/or mod
2. Go inside the game's folder (ex. `C:\Program Files (x86)\Steam\steamapps\common\Half-Life 2 Update` for Half-Life 2 Update)
3. Download and extract Metamod:Source 1.11.0+1155 inside your game's `hl2` folder
- https://mms.alliedmods.net/mmsdrop/1.11/mmsource-1.11.0-git1155-windows.zip
4. Download and extract SourceMod 1.11.0+6968 inside your game's `hl2` folder
- https://sm.alliedmods.net/smdrop/1.11/sourcemod-1.11.0-git6968-windows.zip
5. Go to your game's `hl2\addons\sourcemod\plugins` folder and move every `.smx` file to the `disabled` folder (create the folder if it does not exist)

## How to install and launch Half-Life 2 Adaptive Music Mod 
1. Head to the "Releases" section on GitHub (right side of the project on GitHub), choose the version you want to use, and download the `hl2-amm-version.zip` file
2. Extract it inside your game's **root** folder (ex. `C:\Program Files (x86)\Steam\steamapps\common\Half-Life 2 Update` for Half-Life 2 Update)
3. Launch the game from Steam or the `hl2.exe` executable
4. For debugging only: Follow the following documentation to add arguments when launching your game: https://help.steampowered.com/en/faqs/view/7D01-D2DD-D75E-2955
- Add `-console` to launch the game with the command console. Useful commands are at the end of the README
- Add `-allowdebug` to show debugging information in the console and on screen

## How to alpha-test
- Interact within the Discord server here: https://discord.gg/sG9evmn7zk
- Report isues here: https://github.com/ManuHeel/hl2-amm/issues

## Useful console commands
- `map map_name`: Load the "map_name" map
