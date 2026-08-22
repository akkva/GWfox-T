<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/2ad46a6e-58c2-4683-91ca-37e3896b4f90">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/522c1641-921f-45ce-91b6-e423e70fcb9b">
<img alt="Preview">
</picture><br><br>
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
* `gwt.atbc`: Enable compatibility with the Adaptive Tab Bar Colour extension.
* `gwt.ac`: Manually Specify Accent Color (*Edit `--bg0` in `.css` files to customize*).
