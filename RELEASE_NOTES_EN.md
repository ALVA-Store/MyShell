# MyShell v1.2.0 — Welcome & Personalization Update 🎮

MyShell 1.2.0 puts customization first, with a PS5-inspired welcome experience, editable profiles, flexible carousel options, and per-game artwork choices.

## What's new
- **New welcome screen:** PS5-inspired visual style, animated particles, smoother transition into Home, and an optional profile prompt that can be disabled in Settings.
- **Editable player profile:** change your name and choose an included avatar or supply your own PNG images in `ux0:/data/MyShell/profile/`. Use **SELECT** on the welcome screen to edit.
- **Customizable game carousel:** select a limit of **6**, **10**, or **unlimited** games per category. Unlimited shows all discovered games in Home and removes the separate Game Library shortcut from the carousel.
- **Artwork source per game:** decide whether covers, backgrounds and logos come from SteamGridDB, the game's original assets (if available), custom files, or automatic fallback. Different assets can use different sources.
- **Improved Game Library and UI:** refined selection outline, cleaner bottom-bar spacing with music controls, updated Settings icons and button prompts.
- **Localization improvements:** more consistent translations in Spanish, English, Portuguese, German, Italian and Polish.

## How to update from v1.1.0
1. Back up `ux0:/data/MyShell/` (including config, SteamGridDB API key, artwork, and profile files).
2. Download **MyShell.vpk** from this release's **Assets** section — not GitHub's automatic source archives.
3. Close MyShell. Install the VPK over your current installation using VitaShell. **Do not uninstall the previous version.**
4. Launch MyShell and check the welcome screen, profile settings, the carousel limit and saved artwork preferences.

**Title ID:** `MYSH00001` (unchanged). The update is intended to preserve user data; a backup is still strongly recommended.

## Notes
- You can skip the welcome screen from Settings → User Experience.
- Custom avatars: `ux0:/data/MyShell/profile/*.png`.
- Custom game art: `ux0:/data/MyShell/covers/`, `backgrounds/`, `logos/`.
- Some games do not include original background or logo assets. Unavailable sources are not selectable.
- Background music remains **Beta** and ends when launching a separate game; temporary stutters may occur under load.
- SteamGridDB requires each user to enter a personal API key. It is not included with MyShell.
- Direct PSP game launching may require the separately installed `RETROLNCR` helper.

**Requirements:** A homebrew-enabled PS Vita and VitaShell. MyShell is an unofficial launcher, not a full operating-system replacement.

**Bug reports:** https://github.com/ALVA-Store/MyShell/issues

**Support development:** https://www.paypal.com/paypalme/alvadesigns00

Review rights to distribute any bundled third-party artwork, music, icons and fonts before publishing the release.
