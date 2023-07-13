HaZardModding Singleplayer Fix for Star Trek Elite Force 2 (2003)

This fixes issues with the Singleplayer that come from overlooked bugs.
There are no gameplay changes and no changes to the Gamecode.
The Idea is to keep the game as it is but cure it from anoying
events that are mostly caused by bugs.

Compatibility
==================================
+ Compatible with both, the offical 1.1 and gog relase.
+ Compatible with your Savegames.
- Might not be fully compatible with Mods that change Level Scripts.
- Might not be fully compatible with Mods that change Menus.


Changes/Fixes - Version 1.00
==================================
- Reduced kockback of Alien Commander from Mission 11 by a factor of 10
to prevent players getting killed by fall damage rather than the actual
projectile damage.
- Remove Granade Launcher from the inventory because it was doing to much
splash damage on Engineering Level at Mission 6
- Fixed Crate Monster being invisible on Mission 7
- Fixed Floating/Gravity bug in Mission 6 Exterior


Affected Files:
==================================
models/projectile/projectile-commander-gooball.tik
models/projectile/projectile-commander-missile.tik
models/projectile/projectile-cmdr-missile-turret.tik
maps/global_scripts/global_playerLoadout.scr
maps/m7l1b-attrexian_colony.scr
maps/m7l1a-attrexian_colony.scr
maps/m6-exterior.scr