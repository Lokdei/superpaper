# Installation on linux

## Recommended way

This will allow Superpaper to integrate the best with your system theme and icons.  
See the above example screenshot from Manjaro KDE.

### Install wxpython:

Because of the differences between Linux distributions the installation options differ for wxpython:

- Arch / Manjaro: `sudo pacman -S python-wxpython`
- Debian / Ubuntu and relatives: `sudo apt install python3-wxgtk4.0`
- Fedora : sudo dnf install `python3-wxpython4`
- Special configurations: [wspython.org](https://wxpython.org/pages/downloads/)

### Install superpaper from PyPI

Superpaper is available from [PyPI](https://pypi.org/project/superpaper).

```sh
# Pip is also bundled with python
# To download python go to https://www.python.org/downloads/
pip3 install --user --upgrade superpaper
```

## Experimental way

Somewhat experimental AppImage package is available on the [releases page](https://github.com/hhannine/superpaper/releases).  
The AppImage will run once you make it executable: `chmod +x superpaper-2.0.0-x86_64.AppImage`

## Snaps

Snaps are currently not packaged, however for reference: To install the Snap (if available) you need to install it from the downloaded file with:

```
sudo snap install superpaper_1.2.0_amd64_experimental_classic.snap --classic --dangerous
```

# Coninue reading

[Continue](./README.md/##Installation) reading where you left.
