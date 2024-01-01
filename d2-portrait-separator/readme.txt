Portrait Gender Separator
GitHub: https://github.com/D2-mods/Portrait-Gender-Separator-for-IE-games
Installs on: BG:EE, BG2:EE, IWD:EE, EET (tested on v2.5/v2.6)


Info:
- Adds portraits to the male or female portrait lists.
- Uses a M_*.lua file to add portraits to each list.
- All the normal rules for portrait files for the EEs apply.
- To avoid issues, filenames should be 7 characters or less.

Instructions:
- Put portraits in either the mod folder or the regular Portraits folder.
- Run the installer.
- Files are copied to the override and filenames are grabbed for the M_*.lua file.

--

Additional info:

Mod folder:
- All portraits in the (f) folder are added to the female list.
- All portraits in the (m) folder are added to the male list.
- If you want a portrait to appear in both lists, just put it in both the (m) and (f) folders.
- These folders can also be used to archive your portraits for quick reinstall.

Portraits folder:
- Filenames starting in F will be added to the female list (does not need to be capitalized).
- Filenames starting in M will be added to the male list.
- Files are copied to the override, where they are only selectable if added by a .lua file.

More info: 
- After install, any portraits starting in M or F should be moved/deleted from the Portraits folder.
- The portraits in this folder and from the .lua file are part of separate lists.
- Both will appear when clicking through the portraits in the game if both exist.

--

Notes:
- The mod folder has priority if there are different portraits with the same filename.
- Lines will not be duplicated in the .lua file if a portrait is found multiple times.


Updates:
v1.7 - now compatible with Infinity UI++ (tested with v0.64 Beta)
v1.6 - LUA function is written inlined, then copied to override
v1.5 - Rewrote the installer. It's more efficient + closed one potential (though unlikely) issue.
v1.4 - changed backup folder to weidu_external
v1.3 - minor update, just tightens up some things during install
v1.2 - fixed smaller portraits not appearing if you didn't have a file ending in M
v1.1 - added missing folders
