# Firefox UI Tweaks

A custom stylesheet (`userChrome.css`) to enhance and modernize the Firefox user interface. This theme focuses on softer edges, subtle shadows, rounded web page content, and a cleaner overall aesthetic.

## Features & Styling Changes

Here is a detailed breakdown of the styling changes introduced by `firefox-ui-tweaks.css`:

### 1. Tab Bar & Tabs
- **Cleaner Tab Separators:** Removes the default dividing lines before and after individual tabs for a seamless look.
- **Dynamic Tab Opacity:** Unselected tabs are semi-transparent (50% opacity) and smoothly fade to 90% opacity on hover.
- **Enhanced Selected Tab:** The active tab is highlighted with a 10px rounded border and a subtle drop shadow, making it gently stand out from the background.
- **Transparent Toolbar:** Sets the tab toolbar background to transparent for a cleaner integration with the OS window.
- **Vertical Tabs:** Hides the "New Tab" button specifically when using vertical tabs orientation to declutter the interface.

### 2. URL Bar / Address Bar
- **Modern Appearance:** Adds a prominent 16px border radius to the URL bar for a sleek, pill-like shape.
- **Depth and Shadows:** Applies a soft drop shadow (`rgba(0,0,0,0.15)`) to give the address bar some depth against the browser's background.
- **Animations:** Smooth CSS transitions are applied to the box-shadow and border-radius for an interactive feel.

### 3. Web Page Content Area (Floating Effect)
- **Rounded Web Pages:** The main browser content area (where web pages actually render) is given a 10px border radius and hidden overflow.
- **Container Padding:** Introduces slight padding around the main tab box, creating a small gap between the web page content and the browser window edges. This creates a stylish "floating" or "contained" effect for web pages.

### 4. Status Panel (Link Hover Previews)
- **Floating Status Text:** Completely redesigns the link preview pop-up (usually found at the bottom left) to look like a floating dark-mode tool-tip.
- **Sleek Design:** Features a pure black (#000000) background with crisp white (#ffffff) text, an 8px border-radius, and a pronounced drop shadow (`rgba(0,0,0,0.4)`).
- **Positioning:** Adjusts the padding to pull the status panel slightly away from the exact corner of the window.

### 5. Custom Bookmark Styling
- **Specific Highlight:** Includes a rule to highlight any bookmark item pointing to GitHub (`github.com`), giving it a clear white background aesthetic with a distinct light-grey hover effect.

## Installation

To use these styles in Firefox:

1. Type `about:config` in your Firefox address bar, accept the warning, and ensure that the preference `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`.
2. Type `about:support` in your address bar and click the **"Open Folder"** button next to **"Profile Folder"**.
3. Inside your Profile folder, create a new folder named `chrome` (if one doesn't exist already).
4. Save or copy the contents of `firefox-ui-tweaks.css` into a new file named `userChrome.css` inside that `chrome` folder.
5. Restart Firefox completely to apply the new theme.
