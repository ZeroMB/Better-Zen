# Better Zen Browser

A collection of Zen Browser configuration flags and CSS customizations to enhance your browsing experience with improved UI, functionality, and performance optimizations.

![Preview](https://github.com/user-attachments/assets/f38230a7-09e2-439e-88e8-57b41c351d76)

## Features

- 🎨 Custom CSS styling support with advanced UI modifications
- 🛠️ Browser toolbox debugging capabilities
- 📌 Enhanced workspace and tab management
- 🎵 Advanced audio controls and indicators
- 🔍 Floating URL bar with blur effects
- 📋 Customizable extension menus and context menus
- ⚡ Optimized performance and visual enhancements

## Installation

### Step 1: Enable Custom CSS

1. Open Zen Browser and type `about:config` in the address bar
2. Click "Accept the Risk and Continue"
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Set the value to `true` to enable custom CSS support

### Step 2: Apply CSS Files

1. Find your Zen Browser profile folder:
   - Type `about:profiles` in the address bar
   - Look for "Profile: default" and click "Open Directory" under the 'Root Directory' section

2. Create a new folder named `chrome` in your profile directory (if it doesn't already exist)

3. Place the CSS files from this repository into the `chrome` folder

4. Restart Zen Browser to apply changes

### Step 3: User Customization Flags

Create and configure these custom flags in `about:config`:

| Config | Value | Usecase |
|--------|-------|---------|
| `user.context-menu` | `true` | Enhanced context menu styling and functionality |
| `user.extension-menu` | `true` | Improved extension menu appearance |
| `user.extension-menu.grid-layout` | `true` | Grid layout for extension menu items |
| `user.extension-menu.pinned` | `true` | Pin frequently used extensions in menu |
| `user.floating-urlbar` | `true` | Floating URL bar with modern design |
| `user.floating-urlbar.disable-blur` | `true` | Disable blur effect on floating URL bar |
| `user.floating-urlbar.blur-browser-container-only` | `true` | Apply blur only to browser container behind URL bar |
| `user.audio-indicator` | `true` | Enhanced audio playing indicators on tabs |
| `user.audio-indicator.disable-dancing-tab-icon` | `true` | Disable animated tab icon for audio playback |
| `user.audio-indicator.disable-better-audio-button` | `true` | Disable enhanced audio control button |
| `user.audio-indicator.hide-in-media-controls` | `true` | Hide audio indicator in media controls |
| `user.findbar` | `true` | Improved find bar styling and positioning |
| `user.sidebar` | `true` | Enhanced sidebar appearance and functionality |
| `user.hide-tabs-close-button` | `true` | Hide close button on tabs for cleaner look |
| `user.hide-link-status` | `true` | Hide link status tooltip at bottom of browser |
| `user.hide-scroll-bar` | `true` | Hide scrollbars for minimal interface |
| `user.hide-split-highlight` | `true` | Remove split view highlighting |
| `user.minimal-border-color` | `true` | Use minimal border colors for cleaner appearance |
| `user.hide-Open-All-in-Tabs-in-bookmarks` | `true` | Hide "Open All in Tabs" option in bookmarks |
| `user.bleeding-corners-issue-fixed` | `true` | Fix visual bleeding corners issue |
| `user.hide-star-icon-in-url-suggestions` | `true` | Hide star icon in URL suggestions dropdown |
| `user.hide-search-with-google-suggestion` | `true` | Hide "Search with Google" suggestion |
| `user.hide-url-permission-icon` | `true` | Hide permission icons in URL bar |
| `user.hide-url-container-icon` | `true` | Hide container tab icons in URL bar |
| `user.hide-url-bookmark-icon` | `true` | Hide bookmark icon in URL bar |
| `user.hide-url-plp-icon` | `true` | Hide PLP (Picture-in-Picture) icon in URL bar |
| `user.add-essentials-separator` | `true` | Add visual separator in essentials area |
| `user.zen-menu-button` | `true` | Enhanced Zen menu button styling |
| `user.remove-pinned-separator` | `true` | Remove separator between pinned tabs |
| `user.hide-workspace-indicator` | `true` | Hide workspace indicator from interface |
| `user.workspace-custom-icons` | `true` | Use custom icons for workspaces |
| `user.floating-toolbar` | `true` | Enable floating toolbar design |
| `user.borderless-container` | `true` | Remove borders from container elements |
| `user.more` | `true` | Small UI Improvements |

### Step 4: Browser Configuration

Set these flags in `about:config`:

| Config | Value | Usecase |
|--------|-------|---------|
| `zen.view.compact.toolbar-hide-after-hover.duration` | `150` | Toolbar hover duration in milliseconds |
| `zen.view.grey-out-inactive-windows` | `false` | Prevent theme color change when window loses focus |
| `zen.urlbar.replace-newtab` | `false` | Maintain normal 'New tab' behavior |
| `zen.workspaces.open-new-tab-if-last-unpinned-tab-is-closed` | `true` | Open new tab when last unpinned tab is closed |
| `devtools.debugger.remote-enabled` | `true` | Enable browser toolbox for live editing |
| `devtools.chrome.enabled` | `true` | Enable browser toolbox shortcut |
| `zen.theme.essentials-favicon-bg` | `false` | Disable highlight background in essential tabs |
| `browser.tabs.groups.enabled` | `true` | Enable tab groups functionality |
| `browser.tabs.loadBookmarksInTabs` | `true` | Open bookmarks in new tabs |
| `zen.theme.gradient.show-custom-colors` | `true` | Enable custom theme color gradients |
| `zen.workspaces.show-workspace-indicator` | `false` | Hide workspace indicator from UI |
| `browser.urlbar.trimURLs` | `false` | Show full URLs instead of trimmed versions |
| `media.videocontrols.picture-in-picture.enable-when-switching-tabs.enabled` | `true` | Enable automatic picture-in-picture when switching tabs |
| `zen.widget.linux.transparency` | `true` | Enable window transparency on Linux |

## Troubleshooting

**CSS not loading?**
- Ensure `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`
- Verify CSS files are in the correct `chrome` folder within your profile directory
- Restart Zen Browser after making changes

**Flags not working?**
- Double-check flag names are spelled exactly as shown (case-sensitive)
- Ensure values are set correctly (true/false)

**Want to revert changes?**
- Set flags back to their default values or delete custom flags
- Remove CSS files from the `chrome` folder
- Restart Zen Browser

## License

This project is open source and available under the [MIT License](LICENSE).
