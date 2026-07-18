<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/43f302fd-b7be-4417-9d6f-41ffd69ae71d">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/b2174c12-8d90-43e6-a8e1-1c46ae91e398">
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

## Window Corners
For a Safari-like look, follow these steps:
1. Terminal: Run these commands to set the corner radius:
   * Apply: `defaults write org.mozilla.firefox NSConvolutionOverride1 -float 26`
   * Restore: `defaults delete org.mozilla.firefox NSConvolutionOverride1`
2. CSS: Set `--br0` to `19px` in `userChrome.css` file.
