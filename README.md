<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/a6440399-e29a-4013-95fc-d4e38e59a466">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/329633dd-75a2-4a57-b95e-5da160edbb09">
<img alt="Preview">
</picture><br><br>
<a href="https://github.com/akkva/GWfox-T/archive/refs/heads/main.zip"><img alt="GWfox-T" src="https://img.shields.io/badge/macOS-Tahoe-8e51da?style=for-the-badge"/></a>
<a href="https://www.firefox.com"><img alt="Firefox" src="https://img.shields.io/badge/Firefox-151-8e51da?style=for-the-badge"/></a>
</div>

## Installation
1. Create a `chrome` folder in your Firefox profile directory and move the theme files into it.
2. In `about:config` configure the following preferences:
    * Set to true:
        * `toolkit.legacyUserProfileCustomizations.stylesheets`
        * `svg.context-properties.content.enabled`
    * Set to false:
        * `widget.macos.native-context-menus`
        * `browser.newtabpage.activity-stream.nova.enabled`
3. Restart Firefox.

## Customization
Create these Boolean preferences in `about:config` to customize:
* `gwt.oneliner`: Enable Compact layout.
* `gwt.atbc`: Enable compatibility with the Adaptive Tab Bar Colour extension.
* `gwt.ac`: Manually Specify Accent Color (*Edit `--bg0` in `.css` files to customize*).
