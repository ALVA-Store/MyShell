# Cómo crear tu clave SteamGridDB para MyShell V1

**La clave SteamGridDB solo es necesaria si elegís SteamGridDB para descargar covers, fondos y logos.** Si preferís HexFlow, no necesitás esa clave.

## 1. Registrate y creá la clave

1. Entrá a https://www.steamgriddb.com/ desde el navegador de tu celular o PC.
2. Registrate o iniciá sesión.
3. Abrí el panel de **Preferences → API**: https://www.steamgriddb.com/profile/preferences/api
4. Generá tu clave API (opción *Generate API Key* o equivalente).
5. Copiala exactamente como aparece. Cada usuario debe utilizar su **propia clave**.

## 2. Registrala en la PS Vita

1. Instalá y abrí MyShell.
2. Elegí el idioma en la configuración inicial.
3. Elegí **SteamGridDB** como proveedor de imágenes.
4. MyShell abrirá el teclado de PS Vita y pedirá **SteamGridDB API Key**.
5. Ingresá la clave y confirmá. La consola necesita Wi-Fi para obtener las imágenes.

## 3. Cambiar la clave más adelante

Entrá en **Ajustes → Carátulas/Artwork**; seleccioná **SteamGridDB** y presioná **Cuadrado (□)** para volver a introducirla. MyShell también solicitará la clave si elegís SteamGridDB y no existe una guardada.

## Dónde se guarda

`ux0:/data/MyShell/config/steamgriddb.key`

El programa crea ese archivo en el almacenamiento de la consola. **No hace falta crearlo manualmente.** Si tenés una instalación antigua, el archivo contiene únicamente la clave en texto sin cifrar: no lo compartas ni lo incluyas en backups públicos, capturas, ZIP o repositorios.

El proveedor elegido se guarda en `ux0:/data/MyShell/config/artwork_provider.cfg`.

## Errores comunes

- **La descarga no funciona:** verificá la conexión Wi-Fi, una clave válida y que SteamGridDB tenga imágenes para ese juego.
- **Usé HexFlow:** podés usarlo sin clave SteamGridDB.
- **Quiero cambiar de proveedor:** hacelo desde las opciones de carátulas/artwork dentro de Ajustes.
- **Me pide la clave nuevamente:** confirmá que se guardó correctamente y que la consola permite escribir en `ux0:/data/MyShell/config/`.

SteamGridDB es un servicio de terceros independiente de MyShell. Página oficial: https://www.steamgriddb.com/.
