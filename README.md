# rEFInd Tokyo Night

a Tokyo Night and Tokyo Storm theme for [rEFInd](https://www.rodsbooks.com/refind/index.html)

*sorry I don't have a preview image yet! for some reason the rEFInd screenshot feature is not working on my machine*

### Installation

 1. locate your refind EFI directory. this is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed

 2. create a folder called `themes` inside it, if it doesn't already exist

 3. clone this repository into the `themes` directory.

 4. to enable the theme add `include themes/rEFInd-tokyo-night/theme.conf` at the end of
    `refind.conf`.
    

### Customization
this theme has both Night and Storm variants, with Night being the default. this is achived by having a few different options for wallpaper and selection indicators that you can mix and match to your preferences

to do this, you can update the `banner`, `selection_big`, and `selection_small` sections within `theme.conf` such that each section has one uncommented line with the image of your choice

###### Credits
UI elements: [rEFInd Regular theme](https://github.com/enkia/tokyo-night-vscode-theme)\
colors: [Tokyo Night VSCode theme](https://github.com/enkia/tokyo-night-vscode-theme)