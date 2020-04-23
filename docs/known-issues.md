# Known Issues

### Linux
- Ubuntu (others?): gsettings memory back-end issue:
  - Solution: run superpaper with
  ```
  GIO_EXTRA_MODULES=/usr/lib/x86_64-linux-gnu/gio/modules/ superpaper
  ```

### Windows
- A rare issue where setting the wallpaper fails and leads to a black wallpaper. Might be related to source image properties.

### Mac OS X
- It is not known whether this works at all. If you try it, tell me how it goes!
- The library implementing global hotkeys does not support Mac OS X at this time unfortunately.

