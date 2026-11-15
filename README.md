# MyShell v1.4.0 🎮

**A PS5-inspired, customizable homebrew launcher for PlayStation Vita.**

[Download the latest release](https://github.com/ALVA-Store/MyShell/releases/latest) · [Changelog](CHANGELOG.md) · [Report a bug](https://github.com/ALVA-Store/MyShell/issues) · [English installation guide](docs/UPDATE_V1_1_EN.md) · [Guía de instalación](docs/UPDATE_V1_1_ES.md)

> **Current release:** v1.4.0 · **Title ID:** `MYSH00001` · Unofficial community-developed homebrew. Not endorsed by Sony or SteamGridDB.
>
> This launcher does not ship commercial games or ROMs. Images, sounds, fonts and other third-party resources remain subject to their respective owners' rights.

## What's new in v1.4.0 (includes unreleased v1.3.0 improvements)
- **Future carousel:** a new home layout with large horizontal artwork for the selected game, custom transitions, and Smooth Bounce animations in Future and Classic.
- **Dynamic Themes:** a new visual way to experience MyShell.
- **Animated WebP covers (experimental):** optional user-provided animated horizontal art for Future.
- **CRT effects:** Intense, RGB Phosphors, and experimental CPU Phosphors, now available across the MyShell interface.
- **More control over performance:** adjustable Future artwork preload (3, 5, 7, 10, or 15 nearby horizontal covers).
- **SteamGridDB artwork improvements:** horizontal artwork downloading, better aspect ratio, and caching.
- **Refined Settings and search:** clearer submenus, cleaner navigation, interface polish, and the ability to check for updates inside MyShell.
- **UI consistency:** alignment, selected-tab styling, Game Hub layout, and multilingual refinements.

[Full release notes — English](RELEASE_NOTES_EN.md)

## Install or update
1. Back up `ux0:/data/MyShell/` first.
2. Download **`MyShell.vpk`** from the release's **Assets** (not GitHub's automatic source archives).
3. Close MyShell and install the VPK with VitaShell **over the previous version**. **Do not uninstall MyShell first**.
4. Open MyShell and check profiles, artwork, Game Library, and existing settings.

The Title ID remains `MYSH00001`. Replacing the app does not intentionally erase user data stored under `ux0:/data/MyShell/`, but a backup is recommended.

## Personalization
- Custom avatars: `ux0:/data/MyShell/profile/*.png`
- Covers: `ux0:/data/MyShell/covers/`
- Backgrounds: `ux0:/data/MyShell/backgrounds/`
- Logos: `ux0:/data/MyShell/logos/`
- Game information: press **Square** on a selected game.
- Profile editing: **SELECT** at the welcome screen, or inside Settings → User Experience.
- Carousel size: configurable under Settings → Library.
- SteamGridDB: each user must provide their own API key at [SteamGridDB](https://www.steamgriddb.com/profile/preferences/api); never post that key publicly. HexFlow does not require this key.

## Music and PSP
- Music: `ux0:/pspemu/MUSIC/` or `ux0:/data/MyShell/music/` for compatible MP3/WAV files. `ux0:/music/` is a limited fallback.
- PSP ISO/CSO: `ux0:/pspemu/ISO/`; PSP/PS1 EBOOT.PBP: `ux0:/pspemu/PSP/GAME/<game-folder>/EBOOT.PBP`.
- Direct PSP/PS1 launch requires a separately configured `RETROLNCR` environment.
- Background music is **Beta**: it can stutter during heavy loading and does not follow the player into external games.

## Limitations & credits
MyShell is a homebrew launcher, **not** a replacement operating system for LiveArea. Video playback is not implemented. See [CREDITS.md](CREDITS.md) for project acknowledgments and dependencies. Report issues on [GitHub](https://github.com/ALVA-Store/MyShell/issues).

MyShell is developed by ALVA-Store with AI-assisted development. Review redistribution rights for all bundled artwork, fonts, music and other third-party resources before publishing.
