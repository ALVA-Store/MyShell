# MyShell v1.2.0 — Bienvenida y personalización 🎮

¡MyShell 1.2.0 ya está preparado para una nueva etapa! Esta actualización incorpora una bienvenida inspirada en PS5, perfiles editables, un carrusel configurable y más libertad para elegir imágenes.

## Novedades
- **Nueva bienvenida:** interfaz inspirada en PS5, partículas, transiciones más suaves y opción para saltear esta pantalla desde Ajustes.
- **Perfil personalizable:** cambiá tu nombre, elegí un avatar incluido o utilizá tus propias imágenes PNG en `ux0:/data/MyShell/profile/`. En la bienvenida, pulsá **SELECT** para editar.
- **Carrusel configurable:** elegí **6**, **10** o **sin límite** de juegos por categoría. En Sin límite aparecen todos los juegos detectados en Home y desaparece el acceso separado a Game Library del carrusel.
- **Imágenes a elección:** decidí por juego si el cover, el fondo y el logo usan SteamGridDB, recursos originales cuando estén disponibles, imágenes personalizadas o selección automática.
- **Más mejoras visuales:** outline de selección de Game Library, barras inferiores mejor alineadas, iconos de Ajustes renovados y botones gráficos para las acciones.
- **Idiomas:** correcciones de interfaz en español, inglés, portugués, alemán, italiano y polaco.

## Cómo actualizar desde v1.1.0
1. Hacé una copia de seguridad de `ux0:/data/MyShell/`, incluyendo configuraciones, imágenes, perfiles y clave de SteamGridDB.
2. Descargá **MyShell.vpk** desde la sección **Assets** de esta release, no el ZIP automático de código fuente de GitHub.
3. Cerrá MyShell e instalá el VPK encima de la versión anterior utilizando VitaShell. **No desinstales la versión anterior.**
4. Abrí MyShell y comprobá que tus ajustes anteriores sigan presentes; probá la bienvenida, el perfil y el nuevo límite del carrusel.

**Title ID:** `MYSH00001` (sin cambios). La actualización está pensada para conservar los datos del usuario, pero recomendamos respaldarlos siempre.

## Información importante
- Podés omitir la bienvenida desde Ajustes → Experiencia de usuario.
- Avatares propios: `ux0:/data/MyShell/profile/*.png`.
- Covers, fondos y logos personalizados: `ux0:/data/MyShell/covers/`, `backgrounds/` y `logos/`.
- Algunos juegos no incluyen un fondo o logo original; esas fuentes aparecerán como no disponibles.
- La música en segundo plano continúa en **Beta**: puede trabarse brevemente durante cargas exigentes y se detiene al iniciar un juego externo.
- SteamGridDB necesita una API Key personal del usuario; MyShell no distribuye ninguna clave.
- Para el arranque directo de juegos PSP puede ser necesario instalar `RETROLNCR` por separado.

**Requisitos:** PS Vita habilitada para homebrew y VitaShell. MyShell es un launcher no oficial; no reemplaza LiveArea como sistema operativo.

**Reportar errores:** https://github.com/ALVA-Store/MyShell/issues

**Apoyar el proyecto:** https://www.paypal.com/paypalme/alvadesigns00

Antes de publicar, verificá que tenés permiso para redistribuir imágenes, música, fuentes e iconos de terceros incluidos en el VPK.
