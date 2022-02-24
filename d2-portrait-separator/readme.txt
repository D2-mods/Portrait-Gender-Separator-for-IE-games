Portrait Gender Separator
Installs on: BG:EE, BG2:EE, IWD:EE, EET

Info:
Adds your portraits to the male or female portrait lists.
Uses an M_*.lua file to add portraits to each list.
All the normal rules for portrait files for the EEs apply.
To avoid issues, filenames should be 7 characters or less.

Instructions:
Put portraits in either the mod folder or the regular Portraits folder.
Run the installer.
Files are copied to the override and filenames are grabbed for the .lua file.


Mod folder:
- all portraits in the (f) folder are added to the female list
- all portraits in the (m) folder are added to the male list
- if you want a portrait to appear in both lists, just put it in both the (m) and (f) folders
- these folders can also be used to archive your portraits for quick reinstall

Portraits folder:
- filenames starting in F will be added to the female list (does not need to be capitalized)
- filenames starting in M will be added to the male list
- files are copied to the override, where they are only selectable if added by a M_*.lua file

NOTE: 
I'd recommend to archive, move, or delete files beginning in M or F from the Portraits folder after install.
The portraits in this folder and from the .lua file are part of separate lists.
Both will appear when clicking through the portraits in the game if both exist.


Additional info:
- the mod folder has priority if there are different portraits with the same filename
- lines will not be duplicated in the .lua file if a portrait is found multiple times

