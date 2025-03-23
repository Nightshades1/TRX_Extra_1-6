# TRX_Extra_1-5
TRX_Extra_1-5 Is a Mod for Tomb Raider Remastered 1-5,
Achievements can't be earned by using this mod since EGS will most likely unload the dll (may work on steam though), It's out of the scope of this project and not meant to bypass anything.

# Feature(s) Progress
Many features are for now missing for tr1-3 but you can set maxium health and swim everywhere, It's quite hard to manage 5 games.
|Game  |Feature |Completed|
|:----:|:------:|:-------:|
|TR1-5|Mod & Launcher|✅️|
|TR1-3|Implement Settings to modify in-game Shaders lighting|✅️|
|TR4-6|Implement Settings to modify in-game Shaders lighting|❌|



## Installation TR 1-3
1. (Skip if you are using Steam/Epic Store) Go in your game folder and backup `tomb1.dll` `tomb2.dll` and `tomb3.dll` that can be found in the folder named 1/2/3.
2. (Skip if you are using Steam/Epic Store) Backup `tomb123.exe`.
3. Download the latest `Release.1-3.zip` and directly extract in the game directory, replace all.
4. Start the game with `Start Mod.bat` You can also edit it and add `-dev -noload` (unsure if it work for tr 1-3) if you wish to disable the 2D fake loading screen when loading different levels (not skip FMV though).
5. You may have to locate your savegame and put it in `C:\Users\<Your Username>\AppData\Roaming\TRX`
6. In-Game, press the `INSERT/Ins` key to open the menu, You can also drag/resize it like you want.

## Installation TR 4-6
1. Same steps as TR 1-3 except that the save folder is named TRX2.

## Uninstall
Just replace the files with your backups, on Steam and Epic Online Store, You can directly verify the game integrity and it'll redownload/replace the files that are modified.

## Known Issue for TR 4-5
Going back to certain level that u aren't supposed to, will cause a crash if you use the 'classic' renderer (Especially on Young-Lara levels),<br>
If you go back to the starting levels, your weapon status is set to UNHOLSTERED to avoid weird anims (as this miss Lara Guns anim ...).<br>

# Preview TR 1-3
![image](https://github.com/user-attachments/assets/b2679614-a038-4109-8c95-7527e4155abf)
![image](https://github.com/user-attachments/assets/9a8f21c7-d2a8-4aef-b233-5432513f9fa0)
![image](https://github.com/user-attachments/assets/c7e27150-3fdf-454d-b450-ed15b5f12df9)

# Preview TR 4-5
![image](https://github.com/user-attachments/assets/cd539b22-21f3-4e0a-90fe-c4f4179bf39f)

## This project use
https://github.com/ocornut/imgui<br>
https://github.com/microsoft/Detours

## PS for Aspyr
The TRX level editor is missing ...
