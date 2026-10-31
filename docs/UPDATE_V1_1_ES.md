# Cómo instalar o actualizar MyShell V1.1.0 (ES)

## Antes de actualizar
- Comprobá que tenés una PS Vita con homebrew y VitaShell.
- Cerrá MyShell y hacé una copia completa de `ux0:/data/MyShell/` desde VitaShell o FTP. Contiene los ajustes, clave SteamGridDB, caché e imágenes de la biblioteca.
- No elimines primero la aplicación anterior: al reinstalar sobre el mismo Title ID `MYSH00001` es más fácil conservar el entorno.
- La instalación normal no exige ningún plugin experimental de arranque o retorno.

## Instalación
1. Descargá el archivo adjunto **MyShell.vpk** desde la Release oficial en https://github.com/ALVA-Store/MyShell/releases/latest . Elegí **Assets**, no los ZIP automáticos de GitHub.
2. Copialo a la consola (USB, FTP u otro método que ya uses) y abrí VitaShell.
3. Seleccioná el VPK e instalalo. Si pide confirmar actualización/reemplazo, aceptá únicamente si corresponde a `MYSH00001`.
4. Volvé a LiveArea, abrí MyShell y comprobá que sigan tus favoritos, las carátulas, los temas y la API Key.
5. Si la burbuja no aparece, verificá `ux0:/app/MYSH00001/`, revisá si hubo error de instalación y probá `Refresh LiveArea` desde VitaShell. No borres carpetas a ciegas.

## Probar las novedades
- Game Library: abrí PS Vita o PSP, llegá a la portada Game Library y accedé a la biblioteca de la plataforma.
- Música: empezá a reproducir un MP3, salí a otra sección y tocá SELECT. El mini permite L1/R1, X y Círculo/SELECT.
- Temas: Ajustes > Temas; elegí uno de los temas disponibles.
- SteamGridDB: Ajustes > Artwork; revisá API Key y actualizá la biblioteca si faltan imágenes. La conexión de red es obligatoria para descargas.
- Desinstalación: primero verificá el diálogo **Cancelar**. No pruebes **Desinstalar** sin copia de seguridad y sin usar una app prescindible.

## Precaución con los datos
La configuración de MyShell vive en `ux0:/data/MyShell/`, fuera del contenido `app0:` del VPK. No se borra expresamente al instalar la actualización sobre la versión anterior. Esto no es una garantía para todas las consolas, por lo que se recomienda siempre respaldar. La desinstalación de juegos/apps sí puede modificar datos del usuario; respalda partidas y datos importantes.

## Qué NO hace V1.1
No reemplaza LiveArea como sistema operativo, no reproduce películas y no mantiene la música cuando se inicia un juego externo. PSP requiere `RETROLNCR` y un entorno PSP/PS1 compatible.

## Si aparece un error
Abrí https://github.com/ALVA-Store/MyShell/issues y contanos modelo de PS Vita, almacenamiento SD2Vita/ux0, firmware, instalación, pasos para reproducir y capturas. No publiques tu clave SteamGridDB.
