# Superpaper

Superpaper is an advanced multi monitor wallpaper manager for **Linux** and **Windows** operating systems, with partial and untested support for Mac OS X.

![](https://raw.githubusercontent.com/hhannine/Superpaper/branch-resources/gui-screenshot.png)

### Support

If you find Superpaper useful please consider supporting its development:

- [Support via PayPal](https://www.paypal.me/superpaper/5)
- [Support via Github Sponsors](https://github.com/sponsors/hhannine)

Github matches your donations done through the sponsorship program!

## Installation

### Linux

An AppImage package is available on the [releases page](https://github.com/hhannine/superpaper/releases).  
The AppImage will run once you make it executable.

For other installation options head over to: [installing on linux](./docs/linux-install.md).

### Windows

A Windows installer and a portable package are available on the [releases page](https://github.com/hhannine/superpaper/releases).

_Note_:  
You might have to set your background and image settings to `Span` so it is displayed correctly regardless of the settings you give Superpaper.  
Settings -> Personalization -> Background -> Choose a fit -> Span

### Max OS X

You must build and run the project, see [development-macos](./docs/development-macOS.md).

## Usage

You can either:

- Open Superpaper (GUI mode)
- Access superpaper from the tray menu (GUI mode)
- Call it from the [command-line](./docs/cli-usage.md)

### GUI mode

Customize your profile to your liking:

- Add locations of wallpapers
- Configure a slideshow
- Span an image over multiple monitors
- Modify hotkeys

Example profile configurations are provided and accessible in the Wallpaper Configuration.

## Troubleshooting

If you run into issues and Superpaper closes unexpectedly, you can either:

- Look at the logs
- Run Superpaper from the command-line with the switch '--debug' to get debugging prints.

```
python superpaper.pyw --debug
```

## Known issues

[Known issues](./docs/known-issues.md).

## License

[MIT](./LICENSE)
