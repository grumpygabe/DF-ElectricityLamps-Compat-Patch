# DF-ElectricityLamps-Compat-Patch
A compatibility patch for Darkness Falls

⚠️**WORD OF WARNING**:warning:  While this one tested fine in single player, I've been getting *intense* framerate issues on multiplayer as soon as one of these lights gets dropped. 

🛑 Seriously don't put this one on a server or multiplayer game.  I'm *pretty* sure it's a problem with Electricity Lamps and not the patch, but either way, it be busted.

# Requirements
[Darkness Falls](https://dev.azure.com/KhaineUK/_git/DarknessFallsA20) and ocbMaurice's wonderful [ElectricityLamps](https://github.com/OCB7D2D/ElectricityLamps) mod.

# Description
This is a simple compatibility patch to make ocbMaurice's ElectricyLamps mod play nice with Khaine's Darkness Falls.  It removes DF's "Player Lamps" option and places the ElectricityLamps helper blocks into the correct places in the Electricty Basics and Advanced Engineering perks.

# Installation
Drop the "9-ElectricityLamps-DFPatch" in your mods folder.  You will also need ocbMaurice's ElectricityLamps mod (link above), and for the purposes of mods loading in the correct order, I would change the name of that mod's folder to something alone the lines of "8-ElectricityLamps".  This ensures it loads before the compatibility patch.
