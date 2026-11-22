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
2. Set the following preferences in `about:config`:

| Preference | Value |
| :--- | :--- |
| `toolkit.legacyUserProfileCustomizations.stylesheets` | `true` |
| `svg.context-properties.content.enabled` | `true` |
| `browser.nova.enabled` | `true` |
| `browser.newtabpage.activity-stream.nova.enabled` | `true` |

3. Restart Firefox.


## Customization

Create these Boolean preferences in `about:config` to modify the UI:

| Preference | Description |
| :--- | :--- |
| `gwt.oneliner` | Enable compact layout |
| `gwt.toolbar` | Auto-hide the bookmarks toolbar |
| `gwt.toolbox` | Auto-hide the navigator toolbox in "Expand sidebar on hover" mode |
| `gwt.atbc` | Enable compatibility with the Adaptive Tab Bar Colour extension |

---

> [!NOTE]
> The sidebar is hidden by default when collapsed. In "Expand sidebar on hover" mode, the sidebar can still be expanded by hovering over its left edge. To keep the sidebar visible when collapsed, add `gwt.sidebar` as a Boolean preference in `about:config`.
