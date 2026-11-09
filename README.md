# Portrait Gender Separator (for Infinity Engine games)
Download: https://github.com/D2-mods/Portrait-Gender-Separator-for-IE-games/releases  
Installs on: BG:EE, BG2:EE, IWD:EE, EET (tested on v2.5/v2.6/v2.7)

--

Adds your portraits to the male or female portrait lists, appearing after the official portraits. Scans portraits from inside the mod folder, as well as from the regular Portaits folders for each game.

Usage is really simple. Just put your portraits in one of the subfolders in the mod folder, or optionally in the regular portraits folder for the game. Then run the installer.
Files are copied to the override and filenames are grabbed for the M_\*.lua file. If using the Infinity UI++ mod, instead of a .lua file, this mod will patch UI.MENU directly (does not overwrite any previous changes).

See bottom for compatibility info. This mod needs to be installed after Infinity UI++, if using.

> Portrait limit: There seems to be hard limit to the number of portraits that can be added through the UI, including base game portraits. Past the limit, portraits will appear as a black box. I don't know the exact number. I have no issues with around 350 custom portraits in IWDEE.

--

#### Mod folder:
- All portraits in the (f) folder are added to the female list.
- All portraits in the (m) folder are added to the male list.
- If you want a portrait to appear in both lists, you can put it in both the (m) and (f) folders.
- These folders can also be used to store your portraits for quick reinstall.

#### Portraits folder:
- Filenames starting with F will be added to the female list (does not need to be capitalized).
- Filenames starting with M will be added to the male list.

> Note: After install, any portraits starting with M or F should be moved/deleted from the regular Portraits folder. The portraits in this folder and from the .lua file are part of separate lists. Both will appear when clicking through the portraits in the game if both exist.

--

#### Portrait Picker compatibility:
- compatible:
	- BillyYank's Multi-Portrait
	- Dragonspear UI++
	- Infinity UI++
	- lefreut's Portrait Picker (selection screen will only show the small portraits if you have a file ending in M, but the actual game screens will scale down the L-size if you don't have one)
- not compatible:
	- Mr2150's Portrait Picker

> Note: Anything not listed here just means I haven't tested with it.