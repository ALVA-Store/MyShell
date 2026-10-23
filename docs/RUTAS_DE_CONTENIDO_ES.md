# Dónde poner juegos, imágenes y música

Rutas comprobadas en el código de la compilación MyShell V1 del 23 de octubre de 2026.

| Contenido | Ruta | Notas |
|---|---|---|
| PS Vita | `ux0:/app/` | Juegos y aplicaciones ya instalados; MyShell los detecta |
| PSP ISO/CSO | `ux0:/pspemu/ISO/` | Archivo `.iso` o `.cso` |
| PSP/PS1 EBOOT | `ux0:/pspemu/PSP/GAME/<CARPETA>/EBOOT.PBP` | Un juego por carpeta |
| Canciones | `ux0:/music/` | MP3 y WAV; se buscan también subcarpetas hasta profundidad 2 |
| Covers manuales | `ux0:/data/MyShell/covers/` | `TITLE_ID.png`, `.jpg` o `.jpeg` |
| Fondos manuales | `ux0:/data/MyShell/backgrounds/` | `TITLE_ID.jpg`, `.jpeg` o `.png` |
| Logos manuales | `ux0:/data/MyShell/logos/` | `TITLE_ID.png`, `.jpg` o `.jpeg` |
| Clave SteamGridDB | `ux0:/data/MyShell/config/steamgriddb.key` | Mejor introducirla desde MyShell |

`TITLE_ID` representa el identificador exacto que MyShell asigna al juego. Los archivos manuales tienen prioridad frente a los descargados. Un mismo juego puede tener cover, fondo y logo independientes.

### Música

Colocá `MiCancion.mp3` en `ux0:/music/`, o en una subcarpeta. También reconoce extensiones `.wav`, pero el formato PCM reproducible documentado es **44.100 Hz, estéreo, 16 bits**. Para MP3, la compatibilidad depende de la decodificación disponible; archivos dañados o no estándar pueden fallar. Dentro de Music podés actualizar la biblioteca mediante el menú de opciones.

### PSP

MyShell usa el helper con Title ID **`RETROLNCR`** para iniciar directamente los juegos PSP desde el carrusel. El helper y el entorno PSP/PS1 deben estar instalados aparte. No se incluyen juegos ni contenido protegido.

### La carpeta `ux0:/data/MyShell/`

La app crea carpetas de configuración, base de datos y caché cuando las necesita. **No borres indiscriminadamente `config/`**: allí se guarda, entre otras preferencias, tu clave SteamGridDB. Hacé un respaldo de tus imágenes manuales antes de realizar cambios.
