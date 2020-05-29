# Unpacking the game

In the asset reader, click Functions -> Unpack Game Assets -> navigate to "SteamLibrary\steamapps\common\Hydroneer\Mining\Content\Paks" and click open. Select a folder to save the game files in, click open again, wait for the game to unpack

Note: The Asset Editor was not originally designed to work with this version of unreal and CAN NOT currently save files. You will need to edit the data in a hex editor. I use HxD 

# Pak mods

Pak files for the game go into - %LocalAppData%\Mining\Saved\Paks

Hit Win + R and copy paste %LocalAppData%\Mining\Saved then create the Paks folder in that directory.

000-EverythingFree_P.pak - Removes the cost of all buyable items, however at least one coin must still be placed in the buckets
000-MilWaterDura_P.pak - Increases the durability of the Goliath, Ram, Harvester and Water filter to 1 million. Only works for newly purchased items unless you use a lot of repair kits :D

# Save Editor
Saves are located at %LocalAppData%\Mining\Saved\SaveGames

The save editor allows you to view and change all the variables in your game. There's also a few shortcut options available, such as teleporting all items from a shop into your truck, deleteing all dirt and removing pipes placed on top of each other.

Each time an edit is made a backup of the original save will be created and placed into a Backups folder in the apps directory
