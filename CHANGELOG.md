# Changelog — MyShell

## [1.4.0] — 2026-11-15

**This release combines the previously unreleased v1.3.0 improvements with v1.4.0.**

### Added
- Future: a new horizontal-cover carousel layout with tailored opening animation and SteamGridDB horizontal artwork support.
- Smooth Bounce animations for Future and Classic.
- Dynamic Themes: a new home-screen visual experience.
- Optional animated WebP horizontal covers for Future (experimental).
- CRT effects across MyShell: Intense, RGB Phosphors, and CPU Phosphors (Beta).
- User-configurable Future horizontal artwork preload: 3, 5, 7, 10 or 15 images.
- Manual check for MyShell updates from Settings.

### Improved
- Horizontal artwork aspect ratio and masking, image caching, and preload behavior.
- Future carousel spacing, selected tab and Game Hub layout.
- Settings submenus for carousel layout, theme layers, CRT, and performance.
- Search layout, controller/touch navigation, text alignment, and multilingual presentation.

### Notes
- The Title ID remains `MYSH00001`; in-place update supported. Back up `ux0:/data/MyShell/` first.
- Animated WebP and CPU Phosphors are optional experimental features.
- Music continues to be Beta; heavy operations can interrupt playback.

## [1.2.0] — 2026-11-04
### Added
- A PS5-inspired welcome screen with a user profile, particle effects, power button and a configurable skip option.
- Profile editing: user name, built-in and user-supplied PNG avatars; adjustable circular avatar presentation.
- Home carousel limit selector: 6, 10 or unlimited entries per category; unlimited mode hides the separate Game Library entry from the carousel.
- Per-game source selection for cover, background and logo: automatic, original, SteamGridDB or custom artwork when available.
### Improved
- Smooth welcome-to-carousel transition and visual handling of the initial background.
- Game Library selection outline and bottom-bar alignment, including quick music controls.
- Profile editor controls, button graphics, Settings icons and translated User Experience section.
- Six-language interface: Spanish, English, Portuguese, German, Italian and Polish.
### Notes
- The Title ID remains `MYSH00001` for in-place updates. Back up `ux0:/data/MyShell/` before updating.
- Music continues to be Beta; heavy operations can interrupt playback.
- Original game logos/backgrounds are not available for every title, and PSP artwork may have additional limitations.

## [1.1.0] — 2026-10-30
- Game Library for PS Vita and PSP; recently played and installed games on Home.
- App uninstall actions with safeguards, quick music controls, background music Beta and anniversary-style themes.
- SteamGridDB validation and artwork-matching improvements; News and background-transition fixes.

## [1.0.0] — 2026-10-23
- First public release with PS Vita/PSP launcher, Favorites, SteamGridDB/HexFlow images, Store, News, Wikipedia game information, local music and six languages.
