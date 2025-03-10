# TRX-Extra-45
TRX-Extra-45 Is a mod menu for Tomb Raider Remastered 4 & 5

## Installation
1. (Skip if you are using Steam/Epic Store) Go in your game folder and backup `tomb4.dll` `tomb5.dll` and `tomb6.dll` that can be found in the folder named 4/5/6.
2. (Skip if you are using Steam/Epic Store) Backup `tomb456.exe`.
3. Download the latest Release.zip and directly extract in the game directory, replace all.
4. Start the game with `Start Mod.bat` You can also edit it and add `-dev -noload` if you wish to disable the 2D fake loading screen when loading different levels (not skip FMV though).
5. You may have to locate your savegame and put it in `C:\Users\<Your Username>\AppData\Roaming\TRX2`
6. In-Game, press the `INSERT/Ins` key to open the menu, You can also drag/resize it like you want.

## Uninstall
Just replace the files with your backups, on Steam and Epic Online Store, You can directly verify the game integrity and it'll redownload/replace the files that are modified.


## Known Issue
Going back to certain level that u aren't supposed to, will cause a crash if you use the 'classic' renderer (Especially on Young-Lara levels),<br>
If you go back to the starting levels, your weapon status is set to UNHOLSTERED to avoid weird anims (as this miss Lara Guns anim ...).<br>

# Preview of the menu rendered on the game in full-screen
![image](https://github.com/user-attachments/assets/cd539b22-21f3-4e0a-90fe-c4f4179bf39f)

# Reshade Shaders for TR45, make the game lighter and not too dark
### Installation
Download the TR45-Reshade.zip from the latest release and extract it in your game folder<br>
If you wish to run my mod on top of it, you'll need to run the game with `-noegs -nosteam` argument.

# Reshade Preview Before/After image
![before](https://github.com/user-attachments/assets/9bdec1d0-c768-4c61-a4ee-dd9b2a185ddf)
![after](https://github.com/user-attachments/assets/2201e0eb-32f3-46ea-8bd5-e15aec216c58)



## This project use
https://github.com/ocornut/imgui<br>
https://github.com/microsoft/Detours

## PS for Aspyr
The TRX level editor is missing ...
