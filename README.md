# FullBright | FB - The Future of FullBright

## Contact
For any development related issues/bugs/suggestions please visit: https://discord.gg/b35rQvS  

## Download and How To Use
**The download to the jar is here:** https://www.curseforge.com/minecraft/mc-mods/devjg-fullbright

These tips/instructions are listed as steps for readability, but can be executed in any order:  
1. Press the 'B' button to cycle between each FullBright mode - this can be changed in the controls menu.
2. Use /fb or /fullbright to access the GUI. All configurations are available in this menu.
3. You can change the "transition speed" in the GUI, which is how fast and smooth the cycle button will transition from one brightness level to another.  
4. A transition speed of 0 means that the change from one brightness level to the next will be instant.  
5. A higher transition speed will result in a faster fade through brightness levels.
6. Set "Change w/ Light Level" to true to have the mod automatically adjust the brightness level based on the current light level around you.
7. You can disable the FullBright chat messages by turning Notifications to false.

## To-Do
### Short Term:
  - Add one-time message for new users to say how to use the mod in chat on login
  - Add crash detection that reverts settings to default if there's 2 or more crashes
  - Make Auto-Adjust Brightness Level work via an average of brightness levels around the player to avoid flickering
### Intermediate Term:
  - Fix FB not working with all Texture Packs
  - A *secret* overhaul?
### Long Term:
  - Add a "LightFix"
  - Add Shader support
### Completed:
  - ~~Auto-adjust FullBright~~
  - ~~Add a slider instead of 3 options to choose the transition speed custom~~

## Change Logs
### V2.1.0:
- Changed the code a lot.
- Changed increment/transition speeds so they are faster.
- Added linear interpolation while changing between brightness levels to make it more bearable.
- Added chat notification toggle button.
- Changed the name of the keybinding in the controls menu.
- Changed the highest brightness level to be slightly higher than in the previous version to avoid blocklight level 0 still appearing to be slightly dark.

### V2.1.1:
- Fixed the bug where the nextLevel to transition to isn't properly defined on game launch.

### V2.1.2:
- Fixed critical bug that crashed players who have never used the mod before due to them not having an already generated config file.
- Fixed a slight bug with instant mode not notifying of the correct brightness level being set, but instead notifying about the previous light level in chat. (Lazy temporary fix).

### V2.2 - V2.3
- Fixed various issues and crashes.
- Added an auto adjust that allows the user to see shadows until they enter the shadow area, in which case the mod automatically turns the brightness up.
- Changed the button transition speed to a slider so the transition speed can be more customized by the user.
