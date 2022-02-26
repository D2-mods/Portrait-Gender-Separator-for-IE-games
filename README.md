# Portrait Gender Separator (for Infinity Engine games)
Installs on: BG:EE, BG2:EE, IWD:EE, and EET. 

Adds your portraits to the male or female portrait lists, appearing after the official portraits. Will scan portraits from inside the mod folder, as well as from the regular Portaits folders for each game.

Usage is really simple. Just put your portraits either in the regular Portraits folder or in one of the subfolders in the mod folder. Then run the installer. Files are copied to the override and filenames are grabbed for the M_*.lua file.

#### Portraits files:
- should be 7 characters or less
- you need files ending in L and M (possibly S but needs confirming)
- images can be identical dimensions (game will scale down)
- the M file is needed because the L file doesn't seem to get used for smaller sizes when added by a .lua file

#### Mod folder
- all portraits in the (f) folder are added to the female list
- all portraits in the (m) folder are added to the male list
- if you want a portrait to appear in both lists, just put it in both the (m) and (f) folders
- these folders can also be used to archive your portraits for quick reinstall

#### Portraits folder
- filenames starting in F will be added to the female list (does not need to be capitalized)
- filenames starting in M will be added to the male list
- files are copied to the override, where they are only selectable if added by a .lua file

NOTE: 
I'd recommend to archive, move, or delete files beginning in M or F from the Portraits folder after install.
The portraits in this folder and from the .lua file are part of separate lists.
Both will appear when clicking through the portraits in the game if both exist.