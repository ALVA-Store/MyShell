# Música de MyShell V1.1 (ES)

**Ubicaciones recomendadas (cualquier combinación):**

- `ux0:/pspemu/MUSIC/` — carpeta compatible con Adrenaline.
- `ux0:/data/MyShell/music/` — carpeta privada para música de MyShell.

El escáner busca en las dos carpetas. **Solo si no encontró ninguna pista allí**, intenta `ux0:/music/`. Esa ruta nativa puede estar restringida para homebrew incluso si los archivos existen. Si tenías canciones ahí y MyShell no las reconoce, mové una copia a una de las rutas recomendadas.

## Formatos
- MP3 válido y compatible.
- WAV PCM estéreo, 16 bits, 44.1 kHz.
- Hasta 256 pistas en el escáner actual. Admite subcarpetas hasta dos niveles debajo de la raíz de música.

## Reproductor rápido
1. Abrí Media > Music y reproducí una pista.
2. Volvé a las demás secciones de MyShell sin detener la reproducción.
3. Tocá SELECT para abrir el minirreproductor; L1/R1 cambian canciones, X pausa/reanuda, Círculo o SELECT cierra.

La reproducción en segundo plano es una **Beta dentro de MyShell**. No continúa cuando se inicia un juego externo. Cambios intensos de carátulas/fondos o actividad de red pueden provocar pequeños saltos.

Si no encuentra canciones, podés revisar `ux0:/data/MyShell/music_scan_debug.txt`. El log registra el resultado de los escaneos, sin nombres de las canciones.
