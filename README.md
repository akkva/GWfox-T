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
| `gwt.toolbox` | Auto-hide navigator toolbox in "Expand sidebar on hover" mode. |
| `gwt.vertical-tabs-icons` | Keep the website icon rail visible when vertical tabs are collapsed, including in "Expand sidebar on hover" mode. Default: `false`. |
| `gwt.atbc` | Enable compatibility with the Adaptive Tab Bar Colour extension. |
| `gwt.ac` | Enable manual accent color *(Edit `--bg0` in CSS to customize)*. |

---

> [!NOTE]
> **"Expand sidebar on hover":** 
> In this mode, the sidebar is hidden by default when collapsed, but can still expand on hover from the left.
> Set `gwt.vertical-tabs-icons` to `true` in `about:config` and restart Firefox to keep the collapsed icon rail visible instead. Set it to `false` to restore the theme's default hiding behavior. This preference changes the collapsed appearance; it does not change Firefox's Esc shortcut or explicitly reopen a hidden sidebar.

With `gwt.vertical-tabs-icons` enabled in hover mode, the collapsed icon rail reserves space so it does not cover page content. The collapsed rail and expanded panel share the same translucent background and blur, including during width animations. The backing surface uses the navigation toolbar background (`--toolbar-background-color`). An open sidebar tool panel keeps Firefox's normal layout.

With this preference disabled or unset, the original theme styling is preserved. Enable it to also use pill-shaped vertical tabs and new-tab buttons.
