# Changelog — MyShell

## [1.1.0] — 2026-10-30

### Added / Added
- Full **Game Library** pages for PS Vita and PSP, with a separate compact Home carousel displaying recently played / recently installed titles.
- **Uninstall** actions from Game Library / context menus, with a confirmation dialog. The PS Vita path uses the system package promoter; the PSP path allows only direct `.iso`/`.cso` files in `ux0:/pspemu/ISO/`. Important: back up save data before using uninstall.
- **Music background playback (Beta)** inside MyShell, plus **SELECT quick music player** (L1/R1 previous/next; X play/pause; Circle/SELECT close).
- **Anniversary theme options** for PS1, PS2, PS3, PS4 and PS30YEARS inspired interfaces.
- **SteamGridDB API key verification and refresh-library option** for missing covers, backgrounds and logos.

### Improved / Mejorado
- Game title identification / artwork matching for SteamGridDB.
- Background transitions and Game Library entry/preview transitions.
- Local music discovery: `ux0:/pspemu/MUSIC/` and `ux0:/data/MyShell/music/`, with conditional legacy fallback to `ux0:/music/`.

### Fixed / Corregido
- News transition and thumbnail cleanup issue when leaving News.

### Known limitations
- Background audio can stutter under heavy image or network loading and ends when launching an external game.
- `RETROLNCR` is needed for direct PSP launch.
- This project remains a launcher; it does not replace LiveArea, and video playback is not included.

## [1.0.0] — 2026-10-23

First public release: PS Vita and PSP library, game carousel, Favorites, artwork from SteamGridDB or HexFlow, News, homebrew Store, Wikipedia/Wikidata game information, local MP3 and compatible WAV player, and multilingual UI.
