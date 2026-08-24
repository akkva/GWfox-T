<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/7297d2c9-ccff-4255-ade8-680ed0cb2194">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/bea97744-19b9-4c78-b746-dbe8d3817ed8">
<img alt="Preview">
</picture>
<p>This theme is compatible with macOS 26+</p>
</div>

## Installation
1. Create a `chrome` folder in your Firefox profile directory and move the theme files into it.
2. In `about:config` configure the following preferences:
    * Set to true:
        * `toolkit.legacyUserProfileCustomizations.stylesheets`
        * `svg.context-properties.content.enabled`
    * Set to false:
        * `browser.nova.enabled`
        * `browser.newtabpage.activity-stream.nova.enabled`
3. Restart Firefox.

## Customization
Create these Boolean preferences in `about:config` to customize:
* `gwt.oneliner`: Enable Compact layout.
* `gwt.toolbar`: Auto-hide bookmarks toolbar.
* `gwt.atbc`: Enable compatibility with the Adaptive Tab Bar Colour extension.
* `gwt.ac`: Manually Specify Accent Color (*Edit `--bg0` in `.css` files to customize*).
