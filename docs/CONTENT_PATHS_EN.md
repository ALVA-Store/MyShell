# Game, artwork and music locations

Paths verified against the MyShell V1 source archive received on October 23, 2026.

| Content | Location | Notes |
|---|---|---|
| PS Vita apps/games | `ux0:/app/` | Already installed applications |
| PSP ISO/CSO | `ux0:/pspemu/ISO/` | `.iso` or `.cso` files |
| PSP/PS1 EBOOT | `ux0:/pspemu/PSP/GAME/<FOLDER>/EBOOT.PBP` | One game per folder |
| Music | `ux0:/music/` | `.mp3` and `.wav`; up to two nested folder levels |
| Covers | `ux0:/data/MyShell/covers/` | `TITLE_ID.png`, `.jpg`, or `.jpeg` |
| Backgrounds | `ux0:/data/MyShell/backgrounds/` | `TITLE_ID.jpg`, `.jpeg`, or `.png` |
| Logos | `ux0:/data/MyShell/logos/` | `TITLE_ID.png`, `.jpg`, or `.jpeg` |
| SteamGridDB key | `ux0:/data/MyShell/config/steamgriddb.key` | Enter from MyShell's own keyboard |

Use the game's exact MyShell `TITLE_ID` for manual artwork filenames. Manual files take precedence over downloaded assets. WAV support is limited to compatible PCM stereo 16-bit 44.1 kHz files. For PSP direct launch, the separately installed `RETROLNCR` helper and PSP/PS1 runtime are required. No copyrighted games or media are supplied.
