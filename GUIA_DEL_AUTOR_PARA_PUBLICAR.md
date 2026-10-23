# Publicar MyShell V1 en GitHub: pasos para el autor

**Repositorio de destino:** https://github.com/ALVA-Store/MyShell/tree/main

**No pude inspeccionar de forma verificable el contenido remoto actual. Por eso, no reemplaces ni borres el repositorio que ya usa el proyecto.**

## Etapa 0 — Comprobar el paquete

1. Probá el VPK original `MyShell.vpk` de `02_PARA_LA_RELEASE/` en tu propia PS Vita usando VitaShell.
2. Comprobá que arranque, que guarde una clave personal de prueba, que puedas cambiarla en Ajustes, la biblioteca, música, Store y News.
3. Revisá `docs/AVISOS_Y_LICENCIAS.md`: hace falta confirmar permisos de fuentes, audio, gráficos, código y dependencias. No publiques el VPK ni fuentes si contuvieran recursos sin permiso de distribución.
4. Si usaste una clave de desarrollo en la consola, **jamás** la agregues al VPK ni al repositorio.

## Etapa 1 — Respaldar el repositorio actual

1. Entrá en https://github.com/ALVA-Store/MyShell
2. Descargá una copia usando **Code → Download ZIP**, o clonalo con `git clone`.
3. Identificá archivos que ya utilizás para feeds, catálogo, versiones o actualizaciones. Si encontrás archivos preexistentes con el mismo nombre que los documentos de este kit, comparalos antes de reemplazarlos.

## Etapa 2 — README y documentos

1. Copiá el contenido de `01_PARA_EL_REPOSITORIO` al repositorio, **sin borrar lo que ya existe**.
2. Podés utilizar **Add file → Upload files** en el sitio de GitHub o un cliente Git.
3. Editá el `README.md` existente solamente después de compararlo con el nuevo (tenemos README bilingüe).
4. Para una primera entrega alcanza con README, `docs/`, `CREDITS.md`, `CHANGELOG.md`, plantilla de Issues y `.gitignore`.
5. Las fuentes son **opcionales**: no las subas automáticamente hasta resolver licencias y derechos de recursos.
6. Agregá capturas verdaderas de la consola más adelante, en una carpeta `screenshots/`, y luego enlazalas en el README.

## Etapa 3 — Publicar la Release

1. Abrí https://github.com/ALVA-Store/MyShell/releases/new
2. **Choose a tag** → crear `v1.0.0` a partir de la rama principal que corresponda.
3. **Release title:** `MyShell V1.0.0 — First Public Release`.
4. Copiá las notas de `RELEASE_NOTES_EN.md` y, debajo, `RELEASE_NOTES_ES.md`.
5. Adjuntá desde `02_PARA_LA_RELEASE` el archivo **`MyShell.vpk`** (no es necesario adjuntar el ZIP de fuentes ni archivos de compilación).
6. Opcional: adjuntá `SHA256.txt` para que la comunidad pueda verificar el instalador.
7. Revisá el contenido y presioná **Publish release**. El enlace principal del README apunta a `/releases/latest`.

## Etapa 4 — Probar la página

- Abrí el repositorio en modo incógnito para comprobar que el README sea legible.
- Abrí `/releases/latest` y comprobá que se vea `MyShell.vpk` bajo Assets.
- Revisá los enlaces a SteamGridDB y las rutas.
- Confirmá que **no** se hayan subido `build-*`, cachés, tokens, API keys ni archivos personales.
- Comprobá que los archivos preexistentes del repositorio sigan funcionando.

## Importante

El VPK contiene un módulo experimental de arranque como recurso empaquetado, pero **no habilites ni aconsejes instalar plugins taiHEN como parte del procedimiento normal de V1**. MyShell se abre desde LiveArea.

**Texto breve para el repositorio — About:** `A PS5-inspired launcher for PlayStation Vita | Games, music, homebrew store & artwork`.

**Topics sugeridos:** `ps-vita`, `psvita`, `homebrew`, `vita`, `launcher`, `vita2d`, `vitasdk`.
