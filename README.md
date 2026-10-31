# MyShell V1.1.0 🎮

**A PS5-inspired homebrew launcher for PlayStation Vita.**

[Download the latest release](https://github.com/ALVA-Store/MyShell/releases/latest) · [Installation / update (English)](docs/UPDATE_V1_1_EN.md) · [Instalación / actualización (Español)](docs/UPDATE_V1_1_ES.md) · [Changelog](CHANGELOG.md) · [Report a bug](https://github.com/ALVA-Store/MyShell/issues)

> **Release:** v1.1.0 · **Title ID:** `MYSH00001` · Unofficial, community-developed homebrew. MyShell is not endorsed by Sony or SteamGridDB.
>
> Never download commercial games, copyrighted music or other unauthorized content through this repository. MyShell does **not** include any games or ROMs.

## English

### What's new in V1.1.0

- **Game Library:** browse the complete scanned PS Vita or PSP collection separately from the shorter home carousel. The short carousel highlights recently played and recently installed games.
- **Uninstall from MyShell:** uninstall supported PS Vita applications via the console's package mechanism. PSP deletion is limited to individual ISO/CSO files directly under `ux0:/pspemu/ISO/` (not EBOOT.PBP or save data). **Back up your important data first.**
- **News fix:** improved handling when leaving the News tab.
- **Background music (Beta):** keep listening while navigating MyShell's tabs. Audio may still stutter when graphics or network content load, and it **stops when you launch an external game**.
- **Quick music player:** press **SELECT** while a track is active outside Music; **L1/R1** previous/next, **X** pause/play, **Circle or SELECT** close.
- **Anniversary themes:** selectable PS1, PS2, PS3, PS4 and PS30YEARS-inspired themes (third-party trademarks remain with their owners).
- **SteamGridDB:** API-key validation, artwork/library refresh for missing artwork and improved game identification.
- **Background transitions:** smoother artwork/background changes and transitions, including Game Library.

Earlier features remain: game info, Favorites, artwork providers (SteamGridDB or HexFlow), homebrew Store, News and multilingual interface (Spanish, English, Portuguese, German, Italian, Polish).

### Installation / upgrading

1. Use a homebrew-enabled PS Vita with VitaShell. **Back up `ux0:/data/MyShell/` first.**
2. Download **`MyShell.vpk`** from the release **Assets** (do not download the source code ZIP).
3. Close MyShell and install the VPK in VitaShell over the existing app. Keep the **same Title ID `MYSH00001`**; do **not** delete the previous application as an update step.
4. Open MyShell from LiveArea. Verify Game Library, music, themes and your existing settings.
5. For first-time users, select your language and artwork provider.

Personal artwork, configuration and cached files are held in `ux0:/data/MyShell/`; replacing the app VPK does not intentionally wipe those folders. **Always keep a backup; preservation has not been independently verified on every setup.** [Detailed instructions](docs/UPDATE_V1_1_EN.md).

### SteamGridDB API key

If you choose SteamGridDB artwork, each user needs a **personal** API key:

1. Sign in at [SteamGridDB](https://www.steamgriddb.com/).
2. Generate a key in [Profile → Preferences → API](https://www.steamgriddb.com/profile/preferences/api).
3. Enter the key using MyShell's keyboard when prompted, or change it later in **Settings → Artwork** using the API-key option (Square also opens the key editor).
4. V1.1 validates newly entered keys online before saving. For missing artwork, use **Settings → Artwork → Refresh library** (label can vary by language).

The key is stored only on your device in `ux0:/data/MyShell/config/steamgriddb.key`. **Never post this key online.** HexFlow is the alternative artwork provider and does not require a SteamGridDB key.

### Music files and controls

Place supported `.mp3` or `.wav` files in **`ux0:/pspemu/MUSIC/`** or **`ux0:/data/MyShell/music/`**. MyShell also tries `ux0:/music/` **only if no songs were found in the first two locations**; homebrew may not be allowed to access that native folder on every device. Compatible WAV means PCM, stereo, 16-bit, 44.1 kHz. The scanner supports up to 256 tracks. If no songs are found, see `ux0:/data/MyShell/music_scan_debug.txt` and the [music guide](docs/MUSIC_V1_1_EN.md).

### Other content

- PSP ISO/CSO: `ux0:/pspemu/ISO/`
- PSP/PS1 EBOOT.PBP: `ux0:/pspemu/PSP/GAME/<game-folder>/EBOOT.PBP`
- Custom covers: `ux0:/data/MyShell/covers/`
- Custom backgrounds: `ux0:/data/MyShell/backgrounds/`
- Custom logos: `ux0:/data/MyShell/logos/`
- Direct PSP launch relies on the separately installed `RETROLNCR` helper and a compatible PSP/PS1 environment; MyShell does not install it automatically.

### Limitations

MyShell is a launcher, **not** a complete operating system or an automatic replacement for LiveArea. Video/movie playback is not implemented. Background music is Beta and is limited to the MyShell process. Themes are community-inspired visuals; please respect third-party rights. The experimental boot/return modules are not part of normal V1.1 installation.

---

## Español

**MyShell V1.1.0** es un launcher homebrew para PS Vita con una interfaz inspirada en PS5, biblioteca de juegos, música, noticias, información y tienda de homebrew.

### Novedades de V1.1.0

- **Game Library:** biblioteca completa de PS Vita y PSP, separada del carrusel, que ahora destaca juegos usados recientemente y recién instalados.
- **Desinstalación desde MyShell:** permite desinstalar aplicaciones de Vita y eliminar únicamente ISO/CSO individuales de la carpeta PSP correspondiente. **Hacé un respaldo antes de borrar juegos o aplicaciones.** No borra EBOOT.PBP ni partidas guardadas mediante la función PSP.
- **News:** corrección al salir de la sección y gestionar miniaturas.
- **Música global (Beta):** la canción sigue mientras navegás por MyShell, pero no continúa cuando abrís un juego externo. Puede sufrir pequeños cortes durante cargas intensas.
- **Minirreproductor con SELECT:** L1/R1 cambian de pista, X pausa o reproduce y Círculo/SELECT cierra.
- **Temas:** PS1, PS2, PS3, PS4 y PS30YEARS inspirados en el aniversario de PlayStation.
- **SteamGridDB:** validación de la clave API, actualización de imágenes faltantes y mejor identificación de juegos.
- **Fondos:** mejoras en transiciones y cambios de background, también dentro de Game Library.

### Actualizar desde V1.0.0

1. Hacé una copia de seguridad de `ux0:/data/MyShell/`.
2. Descargá `MyShell.vpk` desde los **Assets de la última Release**.
3. Cerrá MyShell e instalá el VPK desde VitaShell **sin desinstalar primero la versión anterior**.
4. Abrí MyShell y verificá que estén tus imágenes, favoritos, temas, biblioteca y API Key.

Conservamos el Title ID `MYSH00001`. La instalación sobre la versión anterior no borra intencionalmente la carpeta `ux0:/data/MyShell/`, pero recomendamos respaldo por seguridad. [Guía de actualización](docs/UPDATE_V1_1_ES.md).

### Configurar SteamGridDB

Creá una cuenta en [SteamGridDB](https://www.steamgriddb.com/) y generá tu API Key en [Profile → Preferences → API](https://www.steamgriddb.com/profile/preferences/api). Elegí SteamGridDB en MyShell e ingresá la clave en el teclado. En V1.1, las nuevas claves se validan en línea. En **Ajustes → Artwork** también podés cambiar la clave y actualizar las carátulas, fondos y logos faltantes. Tu clave se guarda en `ux0:/data/MyShell/config/steamgriddb.key` y no debe compartirse. Si elegís HexFlow no hace falta.

### Dónde colocar música y juegos

- **Música MP3/WAV:** `ux0:/pspemu/MUSIC/` o `ux0:/data/MyShell/music/` (recomendadas).
- **Carpeta alternativa:** `ux0:/music/` (solo se prueba si las otras dos están vacías y puede tener restricciones).
- **PSP ISO/CSO:** `ux0:/pspemu/ISO/`.
- **PSP/PS1 EBOOT.PBP:** `ux0:/pspemu/PSP/GAME/<carpeta-del-juego>/EBOOT.PBP`.
- **Covers, fondos y logos:** `ux0:/data/MyShell/covers/`, `backgrounds/` y `logos/`, respectivamente.

El arranque directo de PSP requiere el helper `RETROLNCR` por separado y un entorno PSP/PS1 compatible. [Guía de música](docs/MUSIC_V1_1_ES.md).

### Límites y soporte

MyShell **no reemplaza completamente LiveArea** ni incluye reproducción de películas. La música en segundo plano es Beta y solo funciona dentro de MyShell. Reportá errores en [Issues](https://github.com/ALVA-Store/MyShell/issues) y compartí ideas en [Discussions](https://github.com/ALVA-Store/MyShell/discussions).

---

## Credits & distribution

Independent homebrew by **ALVA-Store**, with AI-assisted development. Credits and dependencies: see [CREDITS.md](CREDITS.md) and existing project notices. Resources and names belonging to Sony/PlayStation or other third parties are the property of their respective owners. Do not redistribute third-party artwork, audio, or proprietary fonts without permission.
