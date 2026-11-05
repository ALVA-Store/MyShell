# MyShell v1.2.0 🎮

**A PS5-inspired, customizable homebrew launcher for PlayStation Vita.**

[Download the latest release](https://github.com/ALVA-Store/MyShell/releases/latest) · [Changelog](CHANGELOG.md) · [Report a bug](https://github.com/ALVA-Store/MyShell/issues) · [English installation guide](docs/UPDATE_V1_1_EN.md) · [Guía de instalación](docs/UPDATE_V1_1_ES.md)

> **Current release:** v1.2.0 · **Title ID:** `MYSH00001` · Unofficial community-developed homebrew. Not endorsed by Sony or SteamGridDB.
>
> This launcher does not ship commercial games or ROMs. Images, sounds, fonts and other third-party resources remain subject to their respective owners' rights.

## What's new in v1.2.0 / Novedades

- **PS5-style welcome / Bienvenida estilo PS5:** animated particles, smooth transition to the game carousel, profile name and avatar, and an optional welcome screen.
- **Custom profiles / Perfiles personalizados:** rename your profile, choose a bundled avatar or add PNG avatars in `ux0:/data/MyShell/profile/`.
- **Flexible carousel / Carrusel configurable:** choose 6, 10, or unlimited games per category. Unlimited mode presents all games in the carousel instead of the separate Game Library entry.
- **Artwork choice / Selección de imágenes:** choose the source of each game's cover, background and logo: automatic, SteamGridDB, original game assets (when available), or files supplied by the user.
- **Localization / Idiomas:** improvements to Spanish, English, Portuguese, German, Italian and Polish across menus and prompts.
- **Visual polish / Mejoras visuales:** refined Game Library selection and footers, more consistent button icons and refreshed Settings category icons.

[Release notes — English](RELEASE_NOTES_EN.md) · [Notas de versión — Español](RELEASE_NOTES_ES.md)

## Install or update / Instalar o actualizar

1. Back up `ux0:/data/MyShell/` first. / Hacé un respaldo de esa carpeta.
2. Download **`MyShell.vpk`** from the release's **Assets** (not GitHub's automatic source archives). / Descargá el VPK desde **Assets** de la release.
3. Close MyShell and install the VPK with VitaShell **over the previous version**. **Do not uninstall MyShell first**. / Instalá sobre la versión anterior, sin desinstalarla.
4. Open MyShell and check profiles, artwork, Game Library and existing configuration. / Revisá que tu perfil y tus ajustes se conserven.

The Title ID remains `MYSH00001`. Replacing the application does not intentionally erase user data stored under `ux0:/data/MyShell/`, but a backup is recommended.

## Personalization / Personalización

- Custom avatars / Avatares propios: `ux0:/data/MyShell/profile/*.png`
- Covers / Carátulas: `ux0:/data/MyShell/covers/`
- Backgrounds / Fondos: `ux0:/data/MyShell/backgrounds/`
- Logos: `ux0:/data/MyShell/logos/`
- Game information / Información: press **Square** on a selected game.
- Profile editing / Editar perfil: **SELECT** at the welcome screen, or inside Settings → User Experience.
- Carousel size / Cantidad de juegos: configurable under Settings → Library.
- SteamGridDB: each user must provide their own API key at [SteamGridDB](https://www.steamgriddb.com/profile/preferences/api); never post that key publicly. HexFlow does not require this key.

## Music and PSP / Música y PSP

- Music: `ux0:/pspemu/MUSIC/` or `ux0:/data/MyShell/music/` for compatible MP3/WAV files. `ux0:/music/` is a limited fallback.
- PSP ISO/CSO: `ux0:/pspemu/ISO/`; PSP/PS1 EBOOT.PBP: `ux0:/pspemu/PSP/GAME/<game-folder>/EBOOT.PBP`.
- Direct PSP/PS1 launch requires a separately configured `RETROLNCR` environment.
- Background music is **Beta**: it can stutter during heavy loading and does not follow the player into external games.

## Limitations & credits / Limitaciones y créditos

MyShell is a homebrew launcher, **not** a replacement operating system for LiveArea. Video playback is not implemented. See [CREDITS.md](CREDITS.md) for project acknowledgments and dependencies. Report issues on [GitHub](https://github.com/ALVA-Store/MyShell/issues).

MyShell is developed by ALVA-Store with AI-assisted development. Review redistribution rights for all bundled artwork, fonts, music and other third-party resources before publishing.
