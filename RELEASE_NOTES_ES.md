# MyShell v1.1.0 — Game Library y música 🎮

¡Primera gran actualización de MyShell! Llegan la biblioteca completa, los controles rápidos de música, nuevos temas y varias mejoras.

## Novedades
- **Game Library:** mirá todos tus juegos de PS Vita y PSP. El carrusel principal ahora prioriza títulos jugados recientemente y recién instalados.
- **Desinstalación:** eliminá aplicaciones compatibles de PS Vita desde MyShell, con confirmación. En PSP solo se pueden borrar archivos ISO/CSO individuales directamente en `ux0:/pspemu/ISO/`. Hacé un respaldo primero.
- **News:** corrección del cambio de pestañas y la liberación de miniaturas.
- **Música en segundo plano (Beta):** seguí escuchando música por los menús de MyShell. No continúa dentro de los juegos y todavía puede haber pequeños cortes durante cargas pesadas.
- **Minirreproductor con SELECT:** L1/R1 canción anterior/siguiente, X pausar/reanudar y Círculo/SELECT cerrar.
- **Temas especiales:** diseños inspirados en PS1, PS2, PS3, PS4 y PS30YEARS.
- **SteamGridDB:** mejor identificación, verificación de API Key y actualización de imágenes faltantes.
- **Fondos:** transiciones más suaves y mejoras visuales en Game Library.

## Cómo actualizar desde v1.0.0
1. Hacé una copia de seguridad de `ux0:/data/MyShell/`, incluyendo imágenes y configuraciones.
2. Descargá **`MyShell.vpk`** desde **Assets** de esta Release, no el ZIP de código fuente.
3. Cerrá MyShell e instalá el nuevo VPK sobre la aplicación anterior con VitaShell. **No desinstales primero la V1.** El Title ID continúa siendo `MYSH00001`.
4. Abrí MyShell y verificá tus configuraciones y biblioteca.

### Nuevas carpetas para música
Usá `ux0:/pspemu/MUSIC/` o `ux0:/data/MyShell/music/` para MP3 y WAV compatibles. `ux0:/music/` funciona solo como respaldo si no hay canciones en las anteriores y puede tener permisos restringidos en ciertas consolas.

### Clave SteamGridDB
Conseguí tu clave personal en https://www.steamgriddb.com/profile/preferences/api y cargala en MyShell. Las nuevas claves se verifican en línea. No la compartas. HexFlow no necesita clave SteamGridDB.

**Requisitos:** PS Vita habilitada para homebrew y VitaShell. El arranque directo de PSP necesita `RETROLNCR` configurado por separado.

**Reportá bugs:** https://github.com/ALVA-Store/MyShell/issues

MyShell es homebrew no oficial y no incluye juegos comerciales, ROMs ni música protegida.
