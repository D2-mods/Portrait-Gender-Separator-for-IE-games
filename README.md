# Portrait Gender Separator (for Infinity Engine games)
Download: https://github.com/D2-mods/Portrait-Gender-Separator-for-IE-games/releases  
Installs on: BG:EE, BG2:EE, IWD:EE, EET (tested on v2.5/v2.6)

Adds your portraits to the male or female portrait lists, appearing after the official portraits. Will scan portraits from inside the mod folder, as well as from the regular Portaits folders for each game.

Usage is really simple. Just put your portraits either in the regular Portraits folder or in one of the subfolders in the mod folder. Then run the installer. Files are copied to the override and filenames are grabbed for the M_*.lua file.

#### Mod folder
- All portraits in the (f) folder are added to the female list
- All portraits in the (m) folder are added to the male list
- If you want a portrait to appear in both lists, just put it in both the (m) and (f) folders
- These folders can also be used to archive your portraits for quick reinstall

#### Portraits folder
- Filenames starting in F will be added to the female list (does not need to be capitalized)
- Filenames starting in M will be added to the male list
- Files are copied to the override, where they are only selectable if added by a .lua file

NOTE: 
I'd recommend to move or delete files beginning in M or F from the Portraits folder after install.
The portraits in this folder and from the .lua file are part of separate lists.
Both will appear when clicking through the portraits in the game if both exist.

#### Portrait Selector compatibility:
- compatible
	- Dragonspear UI++ portrait picker
	- BillyYank's Multi-Portrait
	- lefreut's Portrait Picker (selection screen will only show the small portraits if you have a file ending in M, but the actual game screens will scale down the L-size if you don't have one)
- not compatible
	- Mr2150's Portrait Picker