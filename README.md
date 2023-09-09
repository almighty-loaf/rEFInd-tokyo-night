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

To try out different variants and indicators, you can update the `theme.conf` file to change which images are used in the `banner`, `selection_big`, and `selection_small` options. For your convenience, all available images are already listed in that file and you can swap out the active ones by altering which lines are commented out via the `#` symbol.

There are also a handful of different fonts and sizes that are unrelated to the Night/Storm variants, which can be similarly controlled with the `font` section.


#### TODO
Add support for the other icon sizes from the Regular theme


##### Credits
UI elements: [rEFInd Regular theme](https://github.com/bobafetthotmail/refind-theme-regular)\
Colors: [Tokyo Night VSCode theme](https://github.com/enkia/tokyo-night-vscode-theme)\
Wallpaper: [Tokyo Aesthetic](https://wallpapercave.com/w/wp6570018)
