# Music in MyShell v1.1 (EN)

Use `ux0:/pspemu/MUSIC/` and/or `ux0:/data/MyShell/music/` for MP3 and compatible WAV tracks. Only when neither location contains detected songs does MyShell try the legacy `ux0:/music/` path, which may be inaccessible to homebrew on some PS Vita setups.

Supported: valid MP3 and WAV PCM stereo, 16-bit, 44.1 kHz. The scanner currently limits the library to 256 tracks and searches subfolders up to 2 levels deep.

Play a song in Media > Music, return to other MyShell menus and press SELECT for the quick player. L1/R1 previous/next, X pause/resume, Circle or SELECT close.

Background audio is Beta and remains active only while MyShell itself is running. Rendering and network load may still cause brief playback stutters. If tracks are missing, inspect `ux0:/data/MyShell/music_scan_debug.txt` (the log does not list song filenames).
