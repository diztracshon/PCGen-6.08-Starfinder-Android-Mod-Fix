##Fix for Android Mod Slot on PCGen 6.08##

A somewhat hacky fix for the way that the Android Armour Mod Slot is implemented in PCGen 6.08 for Starfinder.

###What does it do?###
Adds a new slot to all characters called the Android Slot, and adds a new armour piece called the Android Mod that is free and (in theory) can only be bought by Androids and is the only item that can equipped to the Android Slot, to which Armour Mods can be added. The 'hacky' nature of this fix means that the Android Mod can also be equipped in the Armour Body slot, but this implementation was the easiest way to keep the ability to add armour mods.

###How to install###
1. Download all the files (you don't need the readme)
2. Navigate to your PCGen install directory
3. Copy/move the 'equipmentslots.lst' file to \system\gameModes\Starfinder and replace the file there
4. Navigate back to the install directory
4. Copy/move the other three (3) files (scr_abilities.lst, scr_equip.lst, scr_profs_armor.lst) to \data\starfinder\paizo\core and replace the files there

###Note###
You really have to overwrite the files to get this to work. You could add the scr_abilities.lst, scr_equip.lst, and scr_profs_armor.lst to a new directory if you know how to set that up and really wanted to, but that won't remove the current implementation.

###Help, it didn't work!###
Start an issue and I'll help troubleshoot the issue and maybe update this readme to be more clear (also let me know if you have problems running the code)
