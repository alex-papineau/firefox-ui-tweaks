# Firefox UI Tweaks

## Changes
- **Tabs:** Removed separators, dynamic opacity for inactive tabs, and hover "lift" animations.
- **URL Bar:** Centered pill-shaped design (16px radius), floating shadow, and minimalist icons that fade in on hover/focus.
- **Content Area:** 10px rounded web page corners with a "floating" container effect.
- **Sidebar:** Floating style with 12px rounding, padding, and subtle backdrop blur.
- **Status Panel:** Redesigned link previews as floating dark-mode tooltips.
- **Toolbar Buttons:** Navigation buttons hidden when disabled; smooth hover and click animations for all buttons.
- **Bookmarks:** Specific aesthetic highlighting for GitHub links.

## Installation
1. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in `about:config`.
2. Locate your Profile Folder via `about:support`.
3. Create a `chrome` folder and save `firefox-ui-tweaks.css` as `userChrome.css` inside it.
4. Restart Firefox.
