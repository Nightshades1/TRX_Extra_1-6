# TRX_Extra_1-6
TRX_Extra_1-6 Is a Mod for Tomb Raider Remastered 1-6,
Achievements can't be earned by using this mod since EGS will most likely unload the dll (may work on steam though), It's out of the scope of this project and not meant to bypass anything.

### TR1-3
- [x] Mod & Launcher.
- [x] Implement settings to modify in-game Shaders lighting.
- [x] Add Newgame override to start at a specific level.
- [x] Add Finish level.
- [x] Add water room feature to swim everywhere.
- [x] Add Lara outfit selection. 
- [x] Add Lara feature to find the north.
- [x] Add Lara feature to adjust swimming boundaries.
- [x] Add Lara feature to adjust swim speed.
- [x] Add checkbox for infinite air.
- [x] Add checkbox to disable lava burn.
- [x] Add checkbox to disable water current.
- [ ] Add checkbox to prevent doors initialisation meant to 'disable' doors collision/controls.

### TR4-5
- [x] Mod & Launcher.
- [x] Implement settings to modify in-game Shaders lighting.
- [x] Add Finish level.
- [x] Add level feature to load a specific level.
- [x] Add water room feature to swim everywhere.
- [x] Add Lara outfit selection. 
- [x] Add Lara feature to find the north.
- [x] Add Lara feature to adjust swimming boundaries.
- [x] Add Lara feature to adjust swim speed.
- [x] Add checkbox for infinite air.
- [x] Add checkbox to disable lava burn.
- [x] Add checkbox to disable water current.
- [ ] Add checkbox to prevent doors initialisation meant to 'disable' doors collision/controls.

### TR6
- [x] Implement settings to modify in-game Shaders lighting.
- [x] Original Swimcheat.
- [x] Activate Level selection/skip in the pause menu.

### Mod Interface
- [x] Save/Restore settings.
- [x] Font Size.
- [x] Other Themes.



## Installation TR 1-3
1. (Skip if you are using Steam/Epic Store) Go in your game folder and backup `tomb1.dll` `tomb2.dll` and `tomb3.dll` that can be found in the folder named 1/2/3.
2. (Skip if you are using Steam/Epic Store) Backup `tomb123.exe`.
3. Download the latest release having tr1-3 tag at [https://github.com/Nightshades1/TRX_Extra_1-6/releases/tag](https://github.com/Nightshades1/TRX_Extra_1-6/tags) and directly extract in the game directory, replace all.
4. Start the game with `Start Mod.bat` You can also edit it and add `-dev -noload` (unsure if it work for tr 1-3) if you wish to disable the 2D fake loading screen when loading different levels (not skip FMV though).
5. You may have to locate your savegame and put it in `C:\Users\<Your Username>\AppData\Roaming\TRX`
6. In-Game, press the `INSERT/Ins` key to open the menu, You can also drag/resize it like you want.

## Installation TR 4-6
1. Same steps as TR 1-3 except that the save folder is named TRX2 and only download the release tagged with _tr4-6.

## Uninstall
Just replace the files with your backups, on Steam and Epic Online Store, You can directly verify the game integrity and it'll redownload/replace the files that are modified.

# TR 1-3
![image](https://github.com/user-attachments/assets/c2b4b215-b527-44c6-8393-272dced972dc)


# TR 4-5
![image](https://github.com/user-attachments/assets/8084bbfc-d5c9-4950-adc8-d5981832b586)


# TR6
![image](https://github.com/user-attachments/assets/e5d551a5-b3a7-4833-828d-547f4a96b33e)



## This project use
https://github.com/ocornut/imgui<br>
https://github.com/microsoft/Detours

## PS for the devs of the game(s)
The TRX level editor is missing ... Looks like you don't plan to allows people to build their own levels,
WorldEdit is missing as well.
