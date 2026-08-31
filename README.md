# Sling_modifiers_mod
A simple mod for Mount and Blade2: Bannerlord to add item modifiers (legendary, balanced...) to slings and sling ammunition. Added both positive and negative modifiers. I used the stats for crossbows, bows, bolts and arrows as reference for the numbers. The names should even be localized.

As always it is recommended to backup your save file, but this mod is very basic so no bigger issues should arise. From my own testing, I found that using and later removing the mod in a save file only removes the affected items.

The mod is probally highly compatible, but I only tested it for 1.4.7.

If you want to address the issue yourself you can simply add: modifier_group="bow" to every sling weapon type (wool, braided and reinforced) and modifier_group="bolt" (or arrow instead of bolt) to every ammunition type (stone, chiseled and lead) in the "weapons.xml" file found in C:\YourPathToSteam\steamapps\common\Mount & Blade II Bannerlord\Modules\SandBoxCore\ModuleData\items\weapons.xml. If you want unique modifier groups either use this mod or edit the files "item_modifiers.xml" and "item_modifiers_groups.xml" found under C:\YourPathToSteam\steamapps\common\Mount & Blade II Bannerlord\Modules\Native\ModuleData\.

The issue this mod is adressing appears to be fixed in the beta version 1.5.1.
