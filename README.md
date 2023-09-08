# rEFInd Tokyo Night

**A Tokyo Night and Tokyo Storm theme for [rEFInd](https://www.rodsbooks.com/refind/index.html)**


*Sorry I don't have a preview image yet! For some reason the rEFInd screenshot feature is not working on my machine.*


### Installation

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed.
 2. Create a folder called `themes` inside it, if it doesn't already exist.
 3. Clone this repository into the `themes` directory.
 4. To enable the theme add `include themes/rEFInd-tokyo-night/theme.conf` at the end of
    `refind.conf`.



### Customization
This theme includes both Night and Storm variants, where Night is a tad darker.

This is achived by having a few different options for wallpaper and selection indicators that you can mix and match to your preferences. To do this, you can update the `theme.conf` file to change which images are used in the `banner`, `selection_big`, and `selection_small` options. For your convenience, all available images are already listed in that file and you can swap out the active ones by altering which lines are commented out via the `#` symbol.

There are also a handful of different fonts and sizes that are unrelated to the Night/Storm variants, which can be similarly controlled with the `font` section.


#### TODO
Add support for the other icon sizes from the Regular theme


##### Credits
UI elements: [rEFInd Regular theme](https://github.com/bobafetthotmail/refind-theme-regular)\
Colors: [Tokyo Night VSCode theme](https://github.com/enkia/tokyo-night-vscode-theme)
