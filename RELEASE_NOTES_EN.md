# MyShell v1.1.0 — Game Library & Music Update 🎮

MyShell's first feature update brings a full Game Library, quick music controls, themed visuals and improvements across the launcher.

## What's new
- **Game Library:** browse all discovered PS Vita and PSP games. Home now highlights recently played and newly installed titles.
- **Uninstall apps:** uninstall supported PS Vita applications directly in MyShell, with confirmation. For PSP, only individual ISO/CSO files located in `ux0:/pspemu/ISO/` can be removed. Back up important data beforehand.
- **News:** fixes for tab changes and thumbnail cleanup.
- **Background music (Beta):** music stays playing across MyShell's menus. Playback does not continue into games; brief stutters may still occur during heavy loading.
- **Quick player:** press **SELECT** outside Music while a song is active. **L1/R1** = previous/next, **X** = pause/play, **Circle/SELECT** = close.
- **Anniversary themes:** PS1, PS2, PS3, PS4 and PS30YEARS-inspired visuals.
- **SteamGridDB:** improved matching, API-key validation and refresh of missing artwork.
- **Background artwork:** smoother transitions and improved Game Library visuals.

## How to update from v1.0.0
1. Back up `ux0:/data/MyShell/`, including artwork, settings and the SteamGridDB API key.
2. Download **`MyShell.vpk`** from this Release's **Assets** (not the source-code ZIP).
3. Close MyShell and install it over the old app using VitaShell. **Do not uninstall the old app first.** The Title ID remains `MYSH00001`.
4. Open MyShell and confirm your previous settings and library remain visible.

### New music-folder guidance
MP3 and compatible WAV files: `ux0:/pspemu/MUSIC/` or `ux0:/data/MyShell/music/`. The native `ux0:/music/` folder is used only as a fallback when no tracks are found in the first two folders and may be restricted on some consoles.

### SteamGridDB API key
Get your own personal key at https://www.steamgriddb.com/profile/preferences/api and enter it in MyShell. Newly entered keys are validated online. Never share your key. HexFlow does not require a SteamGridDB key.

**Requirements:** homebrew-enabled PS Vita, VitaShell. PSP launching requires a separately configured `RETROLNCR` helper.

**Report bugs:** https://github.com/ALVA-Store/MyShell/issues

MyShell is unofficial homebrew. No commercial games, ROMs or copyrighted media are included.
