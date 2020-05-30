### Hydroneer Modding project
[![Generic badge](https://img.shields.io/badge/Hydroneer%20Version-1.2.16-orange.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/project%20language-c%2B%2B-green.svg)](https://shields.io/)

Maintained by kaiheilos

# Structure
## /Tools.
 - currently contains:
   - Asset Editor.exe
   - HydroneerSaveEdit.exe
   
## /Pak Mods
 - Pak files for the game go into - `%LocalAppData%\Mining\Saved\Paks`
 - Hit Win + R and copy paste - `%LocalAppData%\Mining\Saved` then create the Paks folder in that directory.
 
 - Currently Contains:
    - 000-EternalDrill_P.pak
    - 000-EverythingFree_P.pak
    - 000-MilWaterDura_P.pak
    - 000-VehicleTorque_P.pak
    - DayNightExtended_P.pak
    - PickupTruckFuel_P.pak 

# Project Usage and Notes:

## Unpacking the game with the Asset Editor
 - In the asset editor, click Functions -> Unpack Game Assets -> navigate to "SteamLibrary\steamapps\common\Hydroneer\Mining\Content\Paks" and click open. Select a folder to save the game files in, click open again, wait for the game to unpack
 - Note: The Asset Editor was not originally designed to work with this version of unreal and CAN NOT currently save files. You will need to edit the data in a hex editor. I use HxD 

## Save Editor

 - Saves are located at %LocalAppData%\Mining\Saved\SaveGames
 - The save editor allows you to view and change all the variables in your game. There's also a few shortcut options available, such as teleporting all items from a shop into your truck, deleteing all dirt and removing pipes placed on top of each other.
 - Each time an edit is made a backup of the original save will be created and placed into a Backups folder in the apps directory
