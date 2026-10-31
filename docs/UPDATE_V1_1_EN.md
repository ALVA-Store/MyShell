# Installing / upgrading MyShell v1.1.0 (EN)

1. Use a homebrew-enabled PS Vita with VitaShell. Close MyShell.
2. **Back up `ux0:/data/MyShell/` first**, including artwork, settings, game matching and your private SteamGridDB key.
3. Download `MyShell.vpk` under the Assets section of https://github.com/ALVA-Store/MyShell/releases/latest (not Source code ZIP).
4. Transfer the VPK to your PS Vita and install it from VitaShell **over the old application without uninstalling v1.0.0 first**. Title ID stays `MYSH00001`.
5. Launch MyShell from LiveArea and verify your music, favorites, artwork, themes and library.

## New functions to test
- PS Vita/PSP Game Library opens from their Home carousel.
- Start a song in Music, leave to another MyShell tab, then press SELECT to open quick player. L1/R1 change tracks, X pauses, Circle or SELECT closes.
- Settings > Themes includes PS1, PS2, PS3, PS4 and PS30YEARS-inspired visuals.
- Settings > Artwork provides SteamGridDB key entry/verification and artwork refresh.
- Test the Uninstall confirmation using Cancel. Use actual uninstall only on dispensable apps after backing up important data.

**Important:** Music in background is Beta and works only while MyShell runs. PSP direct launch requires the optional separately installed `RETROLNCR` helper. MyShell is not an OS/LiveArea replacement and has no video playback.

If MyShell does not appear in LiveArea, check that `ux0:/app/MYSH00001/` exists and installation completed, then try VitaShell's Refresh LiveArea. Never delete folders to troubleshoot without making a backup. Report problems at https://github.com/ALVA-Store/MyShell/issues . Never share your SteamGridDB key.
