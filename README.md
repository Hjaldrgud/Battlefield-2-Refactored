# Battlefield-2-Refractor Refactored
I have refactored the most important/modded original game files of BF2 to make it easier to mod the game. Almost all the .tweak files for weapons, kits, soldiers, missiles, projectiles and vehicles has been reorganized into a more structured and easier-to-mod code. 

<b>FUN FACT:</b>

The game engines of Battlefield 1942 and Battlefield 2 are called respectively “Refractor” a “Refractor 2.0”. Hence my mod name.

<b>What is this mod?</b>

This mod is a barebones one, but one that I have spent well over six months creating. Calling it a mod is kind of a stretch because it’s just the most common files that are modified in Battlefield 2 that has been refactored.

<b>What is refactoring?</b>

“Refactoring is a disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.”. Basically it is cleanup and reordering of the code without changing what the code does.

<b>Why make this?</b>

Because by being more clean and having stuff neatly organized, it makes it much easier and joyful to mod. Prime example is the mutator minimods I’ve included as examples. These minimods has multiple combinations of modifying handheld weapons to operate different. In the regular files the recoil, deviation, zoom and projectile are all defined in the weapon’s tweak file. I have separated them into individual files. The result is I can very easily and quickly change those values how I’d in separate files and tune the game how I’d like. This makes the mutator minimods I’ve included work wonders.

<b>What are mutators?</b>

I’ve played a bit Unreal Tournament, and what I really liked was that the game shipped with mini-mods the game called “mutators”. It is a list of mods that modifies various values like damage, gravity, velocity, headsize and much more and it made the game more fun if one was bored of the regular gameplay. It is a way to spice things up. I have made the same with .zip files that one can easily add or remove by editing the ServerArchives.con file in the mod’s main folder.

<b>Who might be interested in this?</b>

If you just want to play some “vanilla+”-BF2 I think this is pretty much nails it, though I’m obviously biased. Another player type is the modder. If you are an aspiring modder I think this mod would help you immensely in creating your own mod by serving as a basemod. Use this refactored object_server as a base and build new .zips on top of it like I did with the mutators. If you’re remotely interested in starting a mod project I think building something on top of this “mod” is the best way. Anyone are free to use this as a base and create something and redistribute. Just give me a heads up and I’ll check your mod out 😉

<b>Things to note:</b>

The game reads ServerArchives.con from bottom to top. Top .zips gets top priority. That means that If you create mutators yourself which overwrites some files in another mutator, write that mutator on the top. To add a mutator, open ServerArchives.con and remove “rem “ in front of the mutator you want to activate. To deactivate, add “rem “ in front..

No levels are included. You have to paste them there yourself.

I have worked on this for well over six months now, and there has been a lot of trial and error. I think most bugs and typos are gone, but I’m sure there still are some typos/errors left and there is certainly some combinations of mutators that doesn’t work.
