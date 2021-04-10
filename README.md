# Elegant Nord Theme

This Firefox theme is inspired by [firefox-review](https://github.com/fellowish/firefox-review) and [Almost-dark](https://github.com/Neikon/Almost-Dark-Grey-Colorfull-Proton---FirefoxCSS-Themes),
using the easy on the eye [Nord](https://www.nordtheme.com/) color pallete. 

# Gallery
![2021-Apr-10_4](https://user-images.githubusercontent.com/67771985/114287075-a10ed900-9a53-11eb-8b97-fdc8d3c9d9fc.png)

### Toolbar.
* Centered URL
* URL tools are hidden and they show up on hover.

![2021-Apr-10_5](https://user-images.githubusercontent.com/67771985/114287090-b97ef380-9a53-11eb-9965-bd4560f7979c.png)

# Installing

1. [Click here to download](https://github.com/rafamadriz/Firefox-Elegant-NordTheme/releases/tag/v1.0)
2. Open a new tab in firefox and write in url bar `about:support` you should see a list with your firefox data, You only need **"Profile Directory"** , you can now click in "Open Directory" button, or you can navigate to the folder, the address should be similar to following example depending on your system:
  - Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`
- Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXX.default-XXX`
- macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`
3. Once you're in the correct directory, if there is no folder called `chrome`. Create it.
4. Extract the contents of the zip file you downloaded in the first step into the folder `chrome`
    + it should look something like this: 
    ```
    chrome/
          |- userchrome.css
          |- userContent.css
          |- userColors.css
    ```
5. Now go to firefox open a new tab and write `about:config` in the url bar
6. A dialog will warn you, but ignore it, just do it press the `I accept the risk!` button.
7. Search this `toolkit.legacyUserProfileCustomizations.stylesheets` and set to **true**.
8. Restart Firefox

After that you should have a new theme in yout Firefox.
