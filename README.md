# TRX-Extra-45
TRX-Extra-45 Is a mod menu for Tomb Raider Remastered 4 & 5

## Installation
1. Go in your game folder and backup `tomb4.dll` `tomb5.dll` and `tomb6.dll` that can be found in the folder named 4/5/6.
2. Backup `tomb456.exe`.
3. Download the latest Release.zip and directly extract in the game directory, replace all.
4. Right click on `Launcher.exe` and create a shortcut, in the target add `-noegs -nosteam` it is required to play the game without these services (which could prevent the mod to be injected), You can also add `-dev -noload` if you wish to disable the 2D fake loading screen when quick-loading or loading levels that are interconnected (not skip FMV though).

Alternatively, simply rename the Dll's (Steam_Api/EOSSDK-Win64-Shipping) to something else.<br>
The reason is that Steam or Epic Online Store will most likely kill the process and create it on it's own, It's not meant to cheat the achievements or bypass their protection, Opening github issues for such requests you will receive no support.

5. In-Game, press the `INSERT/Ins` key to open the menu, You can also drag/resize it like you want.

## Known Issue
Going back to certain level that u aren't supposed to, will cause a crash if you use the 'classic' renderer (Especially on Young-Lara levels),<br>
You are advised to only use the modern renderer, As a safe measure<br>
If you go back to the starting levels, your weapon status is set to UNHOLSTERED to avoid weird anims (as they are missing).<br>

## TODO
1. Add these features for Tomb Raider Chronicles

## This project use
https://github.com/ocornut/imgui<br>
https://github.com/microsoft/Detours
# Preview of the menu rendered on the game in full-screen
![image](https://github.com/user-attachments/assets/71c21247-897a-4d8f-ab97-8cd509258a17)
