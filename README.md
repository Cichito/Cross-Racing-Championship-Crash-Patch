# Cross-Racing-Championship-Crash-Patch
I originally wrote this patch for a friend of mine who needed it. This uses a vulkan library that replaces the game's base rendering with vulkan along with a modified executable that adds an 8gb patch to the 32bit executable to prevent the game from crashing when many mods are installed

## Q. How do I install this patch?
The installation is quite simple, you have to extract the contents of the archive and copy the contents into the folder where the game executable is located.

## Q. What versions of the game does it work in?
It works in all versions of the game, both the 2005 retail version and the 2018 steam build.

## Q. What does it fix specifically?
Fixes a number of issues within the Invictus Geona engine, particularly memory leaks and culling issues that occur more often if too many mods are installed, such as add-ons Cars and Add-ons Maps. The game tries to allocate all resources in memory but fails, causing slowdowns and crashes.
