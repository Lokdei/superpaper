# Development on linux

Install the following: 

**Software Requirements**
- [Python 3.6+](https://www.python.org/downloads/)

**Python packages**
- Pillow: Pillow is a Python Imaging Library (PIL), which adds support for opening, manipulating, and saving images.
- screeninfo: Python library to fetch location and size of physical screens.
- numpy: NumPy is a general-purpose array-processing package.
- wxpython (tray applet, GUI & slideshow, optional): wxPython is a cross-platform GUI toolkit for the Python programming language.
- system_hotkey (hotkeys, optional): Multi platform system wide hotkeys support for python 3
- xcffib (dependency for system_hotkey)
- xpybutil (dependency for system_hotkey)

### Install wxpython:
Because of the differences between Linux distributions the installation options differ for wxpython:

- Arch / Manjaro: `sudo pacman -S python-wxpython`
- Debian / Ubuntu and relatives: `sudo apt install python3-wxgtk4.0`
- Fedora : sudo dnf install `python3-wxpython4`
- Special configurations:  [wspython.org](https://wxpython.org/pages/downloads/)

```sh
# Run the following command in your terminal to install the python packages
pip3 install --upgrade Pillow screeninfo numpy system_hotkey xcffib xpybutil

# Clone the project
git clone https://github.com/hhannine/superpaper/
```
