# rEFInd Tokyo Night

**A Tokyo Night and Tokyo Storm theme for [rEFInd](https://www.rodsbooks.com/refind/index.html)**

![tokyo-night-square](https://github.com/almighty-loaf/rEFInd-tokyo-night/assets/418354/8b18b862-3978-4f27-b13c-4f794d96bfe9)
*Tokyo Night*
<br>
<br>

![tokyo-storm-square2](https://github.com/almighty-loaf/rEFInd-tokyo-night/assets/418354/825bf73a-6c9b-4795-85b0-b8c61ce567fa)
*Tokyo Storm*
<br>
<br>


### Installation

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed.
 2. Create a folder called `themes` inside it, if it doesn't already exist.
 3. Clone this repository into the `themes` directory.
 4. To enable the theme add `include themes/rEFInd-tokyo-night/theme.conf` at the end of
    `refind.conf`.



### Customization
This theme includes both Night and Storm variants, and a few different selection indicators to fit your preferred style.

To make changes to the theme, open the `theme.conf` file and change which options are active. All lines prefixed with a `#` are ignored, otherwise they are considered active. Each line takes the form `option value` where `option` is the identifier for element of the theme and `value` is what that element will look like. There should only be one active entry for each option.

For your convenience, all included images are already listed in the file, so you can just swap the active entries.

This theme also includes the popular [Tokyo Aesthetic](https://wallpapercave.com/w/wp6570018) wallpaper, with a little baked in blur to improve legibility of icons and text. To use this, activate the appropriate `banner` option for the wallpaper that matches your monitor's aspect ratio. You can of course upload a custom wallpaper of your choosing by placing it in the `wallpaper` directory and editing the active `banner` option accordingly. (For consistency, I recommend using an image that exactly matches your monitor's resolution, or the resolution you configured in the base `refind.conf` config file.)

There are also a handful of different fonts and sizes that are unrelated to the Night/Storm variants as `font` options.


#### TODO
Add support for the other icon sizes from the Regular theme


##### Credits
UI elements: [rEFInd Regular theme](https://github.com/bobafetthotmail/refind-theme-regular)\
Colors: [Tokyo Night VSCode theme](https://github.com/enkia/tokyo-night-vscode-theme)\
Wallpaper: [Tokyo Aesthetic](https://wallpapercave.com/w/wp6570018)
