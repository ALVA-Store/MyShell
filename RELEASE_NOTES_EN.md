# MyShell v1.4.0 — A New Way to Experience Your PS Vita

**This release combines the improvements from the unreleased v1.3.0 and the new features developed for v1.4.0.** It's one of the biggest MyShell updates so far, focused on customization, artwork, smoother navigation, and a more personal home screen.

## Highlights

### Future: An All-New Home Screen Layout
- Introducing **Future**, a new carousel layout with square game covers and a large **horizontal artwork** for the selected game.
- Horizontal artwork support through **SteamGridDB**, with a dedicated download option and fallback images when artwork isn't available.
- Redesigned opening animation: covers assemble, the selected cover expands horizontally, and neighboring covers move aside.
- **Smooth Bounce** animations for both Future and Classic layouts.
- Larger secondary covers, improved spacing, a highlighted active tab, softer outlines, and refined logo/Game Hub alignment.
- Special handling for Music, Game Library, and Store tiles to preserve their original proportions.

### Dynamic Themes
- Introducing **Dynamic Themes**, a new way to experience the MyShell launcher with a fresh visual style.

### Animated Future Covers (Experimental)
- Optional **animated WebP horizontal covers** for Future.
- Advanced users can manually place files named `<TITLE_ID>.webp` in `ux0:/data/MyShell/future_animated/`.
- Only the selected game's animation is played; standard horizontal artwork remains the fallback.
- No automatic animated-cover downloads are required.

### CRT Visual Effects
- CRT effects can now appear throughout the MyShell interface instead of only on the Home screen.
- Choose between **Intense**, **RGB Phosphors**, and **CPU Phosphors (Beta)**, or turn the effect off.
- CRT options are organized in their own submenu, and your selection persists across restarts.

### Performance and Artwork Improvements
- Smarter preloading of nearby Future artworks to reduce visible loading when switching games.
- **Adjustable Future artwork preload** from Settings → Performance: **3, 5, 7, 10, or 15** horizontal covers.
- Better reuse of prepared textures, improved transitions, and separate handling of horizontal and square artwork.
- Full-width horizontal images now preserve the original SteamGridDB aspect ratio without unwanted side cropping.

### Settings, Search, and Usability (Including v1.3.0)
- Reorganized Settings with clearer submenus for carousel design, theme layers, CRT effects, and performance options.
- Choose between **Classic** and **Future** without replacing your existing visual theme.
- Improved search layout and navigation, along with additional interface and alignment fixes.
- Added the ability to **check for MyShell updates from Settings**.
- Refinements to controller/touch navigation, visual consistency, and multilingual interface text.

## How to Update from v1.2.0
1. Back up `ux0:/data/MyShell/` (settings, artwork, profiles, and API key).
2. Download **`MyShell.vpk`** from this release's **Assets** section, not the automatically generated source archives.
3. Close MyShell and install the VPK over your current installation using VitaShell. **Do not uninstall the previous version.** The Title ID stays `MYSH00001`.
4. Open MyShell and check that your library and existing settings are still available.

## Notes
- **Animated WebP** and **CPU Phosphors** are experimental/optional features. Regular PNG artworks remain fully supported.
- If building from source, animated WebP support requires **libwebp** in VitaSDK.
- Back up your current working build and settings before upgrading.

Thank you to everyone following and supporting MyShell. This update is another step toward making the PS Vita home screen feel more modern, customizable, and uniquely yours. ❤️

**Bug reports:** https://github.com/ALVA-Store/MyShell/issues

**Support development:** https://www.paypal.com/paypalme/alvadesigns00
