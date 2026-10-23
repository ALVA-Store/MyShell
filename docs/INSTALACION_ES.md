# Cómo instalar MyShell V1 (PS Vita)

## Requisitos

- Una PS Vita con homebrew habilitado y VitaShell instalado.
- Memoria disponible y, para servicios en línea, conexión Wi-Fi.
- Una clave API personal **solo si elegís SteamGridDB** para las imágenes.
- Para iniciar juegos de PSP/PS1 desde el carrusel: el entorno PSP/PS1 correspondiente y el ayudante de inicio `RETROLNCR` instalados y configurados por separado. MyShell no los proporciona ni los instala automáticamente.

## Instalación

1. Abrí [Releases](https://github.com/ALVA-Store/MyShell/releases/latest) y descargá el archivo `MyShell.vpk` de **Assets**.
2. Copialo a la PS Vita mediante USB, FTP u otro método que uses con VitaShell.
3. Desde VitaShell, localizá el archivo `.vpk` y confirmá su instalación.
4. Volvé a LiveArea y abrí la burbuja **MyShell**.
5. Elegí el idioma, después seleccioná SteamGridDB o HexFlow como fuente de carátulas.
6. Si elegiste SteamGridDB, introducí la clave API con el teclado en pantalla. [Guía detallada](STEAMGRIDDB_ES.md).

## Tus juegos

- **PS Vita:** aparecen los títulos que MyShell detecta en `ux0:/app/`. MyShell no incluye ni instala juegos comerciales.
- **PSP ISO/CSO:** colocá tus copias autorizadas en `ux0:/pspemu/ISO/`.
- **PSP/PS1 EBOOT.PBP:** colocá cada juego compatible en una subcarpeta bajo `ux0:/pspemu/PSP/GAME/`.
- **Arranque directo de PSP:** MyShell espera encontrar el helper `RETROLNCR` en `ux0:/app/RETROLNCR/`. Sin él, una entrada PSP puede aparecer en la biblioteca pero el arranque directo no funcionará. El sistema PSP/Adrenaline y el helper son componentes externos.

Para imágenes y música, consultá [Rutas de contenido](RUTAS_DE_CONTENIDO_ES.md).

## Problemas frecuentes

**Mis juegos no aparecen:** comprobá las rutas, el nombre del archivo y que el contenido ya esté instalado o correctamente copiado; reiniciá MyShell para forzar la detección del inicio.

**SteamGridDB no descarga imágenes:** revisá tu Wi-Fi, que la clave API sea válida y que el juego exista en el catálogo. También podés elegir HexFlow o colocar imágenes manuales con el ID correcto.

**No aparecen las canciones:** usá `ux0:/music/` y archivos `.mp3` o `.wav`. El lector busca hasta dos niveles de subcarpetas. Para WAV, la compatibilidad implementada es PCM, estéreo, 16 bits, 44,1 kHz. Otros formatos WAV pueden detectarse pero no reproducirse.

**No se abre un juego PSP:** revisá que `RETROLNCR` y el entorno PSP/PS1 estén instalados y configurados, y que el archivo del juego exista.

**News/Store no actualizan:** revisá la conexión. News utiliza RSS público de Reddit y puede verse afectado por bloqueos o cambios del servicio. Store usa el catálogo externo VitaHomebrewDB.

**¿Se inicia solo al prender la consola?** No. MyShell V1 se abre desde LiveArea. No instales módulos experimentales ni edites `ur0:tai/config.txt` siguiendo tutoriales de terceros sin respaldo y pruebas.

**Nota:** comprobamos la estructura e integridad del VPK, pero no podemos confirmar desde aquí su instalación en todas las versiones de PS Vita. Probá este VPK exacto en tu consola antes del anuncio público.
