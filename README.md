# MyShell V1 🎮

**A PS5-inspired homebrew launcher for PlayStation Vita.**

[Download MyShell V1](https://github.com/ALVA-Store/MyShell/releases/latest) · [English instructions](docs/INSTALL_EN.md) · [Guía en español](docs/INSTALACION_ES.md) · [SteamGridDB API Key](docs/STEAMGRIDDB_ES.md)

> **V1.0.0** · Application Title ID: `MYSH00001` · Internal version: `01.00`
>
> **Unofficial homebrew project.** MyShell is not affiliated with, approved by, or endorsed by Sony Interactive Entertainment, PlayStation or SteamGridDB.

## English

MyShell brings a console-style launcher to PS Vita, with a PS5-inspired interface, game library, local music playback, homebrew store, news and game information.

### Features in V1

- PS Vita apps/games and PSP/PS1 entries collected into a carousel.
- SteamGridDB or HexFlow artwork provider selected at first launch; manual covers, backgrounds and logos supported.
- Custom artwork for game covers, backgrounds and logos.
- Built-in **Music** for local MP3 and compatible WAV files.
- **Store** using the VitaHomebrewDB catalog (requires internet for new catalog downloads and installs).
- **News** from public Reddit RSS feeds (availability may vary).
- **Game information** via Wikipedia/Wikidata when available.
- Favorites, library options, artwork settings, multilingual interface.
- Languages: Spanish, English, Portuguese, German, Italian and Polish.

**What V1 is not:** It is a launcher, *not* a fully independent operating system or a complete replacement for LiveArea. Video/movie playback is not included in this version. Experimental boot/return modules must not be installed or enabled as a routine part of V1 setup.

### Installation

1. You need a homebrew-enabled PS Vita with VitaShell.
2. Download the **`MyShell.vpk`** file under [Releases](https://github.com/ALVA-Store/MyShell/releases/latest) (under **Assets**, not *Source code ZIP*).
3. Transfer the VPK to the Vita and install it through VitaShell.
4. Open **MyShell** from LiveArea and complete first-time language and artwork setup.
5. When using SteamGridDB, [generate your personal API key](https://www.steamgriddb.com/profile/preferences/api) and enter it in MyShell on your Vita. **HexFlow is the alternate provider and does not require a SteamGridDB key.**

See [full instructions](docs/INSTALL_EN.md), [SteamGridDB walkthrough](docs/STEAMGRIDDB_EN.md), and [music/artwork folders](docs/CONTENT_PATHS_EN.md).

### SteamGridDB API Key (important)

**To download artwork from SteamGridDB, you need your own API Key.**

1. Sign in or create an account on [SteamGridDB](https://www.steamgriddb.com/).
2. Open **[Profile → Preferences → API](https://www.steamgriddb.com/profile/preferences/api)**.
3. Generate and copy your API key.
4. On the Vita, choose **SteamGridDB** during MyShell's first-run artwork setup. Enter your key when the on-screen keyboard opens.
5. To change the key later, go to **Settings → Artwork/Covers**, highlight SteamGridDB and press **Square (□)**.

MyShell stores the entered key locally at `ux0:/data/MyShell/config/steamgriddb.key`. **Do not publish or share this file or your key.** SteamGridDB is an independent third-party service. An internet connection is required to fetch online artwork. [More details →](docs/STEAMGRIDDB_EN.md)

### PSP launching

MyShell scans `ux0:/pspemu/ISO/` and `ux0:/pspemu/PSP/GAME/`. Its direct-launch path relies on the separately installed `RETROLNCR` helper (and an appropriately configured PSP/PS1 runtime). The VPK does **not** install this helper for you. See the installation guide.

---

## Español

**MyShell es un launcher homebrew para PS Vita inspirado en la interfaz de PS5.** Incluye un carrusel de juegos y aplicaciones, música local, tienda de homebrew, noticias e información sobre los juegos.

### Funciones de la versión 1

- Biblioteca de PS Vita, PSP y entradas de PS1.
- Elección inicial entre **SteamGridDB** y **HexFlow** para las imágenes.
- Covers, fondos y logos personalizados.
- Reproductor de **música MP3 y WAV compatible**.
- **Store** con catálogo de VitaHomebrewDB, descargas e instalación de homebrew.
- **News** con noticias de fuentes RSS públicas de Reddit (puede depender de la disponibilidad del servicio).
- Información de juegos mediante Wikipedia/Wikidata cuando existe.
- Favoritos, ajustes de biblioteca, imágenes, idiomas y rendimiento.
- Idiomas: español, inglés, portugués, alemán, italiano y polaco.

**Importante:** MyShell V1 es un *launcher*, no un sistema operativo que reemplace completamente LiveArea. Esta versión **no reproduce películas ni videos**. Los módulos experimentales de arranque/retorno no forman parte de la instalación normal.

### Instalación rápida

1. Necesitás una PS Vita habilitada para homebrew y **VitaShell**.
2. Descargá `MyShell.vpk` desde [Releases](https://github.com/ALVA-Store/MyShell/releases/latest), en **Assets** (no en *Source code ZIP*).
3. Copiá el VPK a la consola e instalalo con VitaShell.
4. Abrí MyShell desde LiveArea y elegí idioma y proveedor de imágenes.
5. Para usar SteamGridDB, registrá tu **clave personal** directamente en el teclado de MyShell.

Guías: [instalación completa](docs/INSTALACION_ES.md) · [clave SteamGridDB](docs/STEAMGRIDDB_ES.md) · [juegos, covers y música](docs/RUTAS_DE_CONTENIDO_ES.md).

### SteamGridDB: tu clave personal

Para descargar imágenes de SteamGridDB, cada usuario debe [registrarse y generar su propia clave API](https://www.steamgriddb.com/profile/preferences/api). Al iniciar MyShell, elegí **SteamGridDB**, ingresá la clave en el teclado que aparece y confirmá. Para cambiarla más tarde: **Ajustes → Carátulas/Artwork → SteamGridDB → Cuadrado (□)**. La clave queda guardada localmente en `ux0:/data/MyShell/config/steamgriddb.key`. **No compartas tu clave.** Si elegís **HexFlow**, no necesitás una clave de SteamGridDB.

### Capturas de pantalla

Se añadirán capturas reales de MyShell V1 en PS Vita. **No se incluyen imágenes de muestra inventadas** en esta entrega.

### Créditos y avisos

MyShell es un proyecto homebrew independiente. Gracias a las comunidades de PS Vita, VitaSDK/vita2d, SteamGridDB, HexFlow-Covers, VitaHomebrewDB, Wikipedia/Wikidata y a las comunidades que aportan contenido público. Los nombres, marcas y recursos de terceros pertenecen a sus respectivos titulares.

Consulta [Créditos](CREDITS.md), [Historial de cambios](CHANGELOG.md) y [Avisos de distribución](docs/AVISOS_Y_LICENCIAS.md).

> No distribuimos juegos comerciales, ISO, ROMs, música ni películas con MyShell. Usá solamente contenido para el que tengas derechos.
