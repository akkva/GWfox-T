## <p align="center"> <b> GWfox-T 🦊 </b> </p>
<p align="center">This theme compatible with Firefox 145+ on macOS Tahoe</p>
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/8918dcfb-7368-4400-b026-8451ba268577">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/428465b1-9c8d-4ff2-80f2-5ff36a9310ed">
<img alt="01">
</picture>

## How to install
- [Download the theme as a zip file](https://github.com/akkva/GWfox-T/archive/refs/heads/main.zip)
- Open your profile directory
  - go to `about:support`
  - click the **Open Folder** button next to your **Profile directory**
- Place the `chrome` folder from the download zip in your profile folder
- Change configurations
  - In the URL Bar, go to `about:config`
  - Set these to true
    - `toolkit.legacyUserProfileCustomizations.stylesheets`
    - `svg.context-properties.content.enabled`
    - `sidebar.animation.enabled`
  - Set `widget.macos.native-context-menus` to false
- Restart Firefox!
## Further customization
- Add `gwt.atbc` to enable [Adaptive Tab Bar Colour](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour)
- Add `gwt.oneliner` to enable Compact layout
## Customizing Accent Color
- Option 1: Follow System Theme Color
  - Sync with the system accent color by selecting a color in System Settings > Appearance.
- Option 2: Manually Specify Accent Color
  - Add Configuration Flag: Open `about:config` and add a new preference named `gwt.ac`
  - Edit CSS Stylesheets: In your `userChrome.css` and `userContent.css` file, modify the value of the `--bg0` variable to your desired color.
