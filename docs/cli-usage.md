# CLI usage

Superpaper supports the following arguments, display specific values are given starting from the first display on the left. Perspectives are not supported at this time.

- "--help"
- "--setimages", list of images to set on your monitors, if given only one it will be spanned across.
- "--inches", optional, expects display diagonals in inches to compute PPIs
- "--bezels", optional, expects display bezels in millimeters
- "--offsets", optional, if image alignment with ppi&bezels isn't quite right you can add additional offset in pixels
- "--command", optional, user can pass a custom command to set the wallpaper.
- "--debug", optional debugging flag.

Perspectives cannot be configured through the CLI currently.

An example using all corrections to set a single spanned image:

```sh
superpaper.py --setimages /path/to/img.png --inches 27 25 --bezels 9.5 7.0 --offsets 0 0 40 -100
```

Offsets are given as a pair-wise list of "horizontal_offset vertical_offset" starting from the first monitor on the left,
i.e. in the above example the display on the left is given no additional offset (0 0) and the display on
the right is given a horizontal offset to the right by 40px and a vertical offset of 100px up (40 -100).

In the custom command, replace '/path/to/img.jpg' by '{image}', i.e. for example with the Gnome command:

```
gsettings set org.gnome.desktop.background picture-uri file://{image}
```

The resulting image is saved into Superpaper/temp/ and then set as the wallpaper.

The option set_command accepts a user defined one-liner to set the wallpaper if your system is not supported out of the box. As a special case, one can tell Superpaper to use feh with a tested and built-in command by setting:

set_command=feh