<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/7297d2c9-ccff-4255-ade8-680ed0cb2194">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/bea97744-19b9-4c78-b746-dbe8d3817ed8">
<img alt="Preview">
</picture>
<p>This theme is compatible with macOS 26+</p>
</div>

## Installation

1. Move the theme files into your profile's `chrome` folder.
2. Configure `about:config` with these preferences:

| Preference Name | Value |
| :--- | :--- |
| `toolkit.legacyUserProfileCustomizations.stylesheets` | `true` |
| `svg.context-properties.content.enabled` | `true` |
| `browser.nova.enabled` |`false` |
| `browser.newtabpage.activity-stream.nova.enabled` |`false` |

3. Restart Firefox.


## Customization

Create these **Boolean** preferences in `about:config` to customize:

| Preference Name | Description |
| :--- | :--- |
| `gwt.oneliner` | Enable Compact layout. |
| `gwt.toolbar` | Auto-hide bookmarks toolbar. |
| `gwt.toolbox` | Auto-hide navigator toolbox when hiding tabs and sidebar. |
| `gwt.atbc` | Enable compatibility with the Adaptive Tab Bar Colour extension. |
| `gwt.ac` | Manually specify accent color *(Edit `--bg0` in CSS to customize)*. |

---

> [!IMPORTANT]
> **"Hide Tabs and Sidebar":** 
> In this mode, the sidebar can still be summoned from the left. However, in Firefox 154+, closing the window or restarting the browser causes the tabs to disappear. To restore the display, simply toggle the sidebar on and off once.
