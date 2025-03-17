# Virtual Desktop Switcher
This AutoHotkey v2 script allows you to switch between virtual desktops on Windows using hotkeys. It supports wrap-around mode, ping-pong mode and quick desktop switching with numeric keys.

## Features
- **Switch Desktops with Hotkeys**: Use `Win + Ctrl + Tab` to switch to the next desktop or `#1` to `#9` to switch to a specific desktop.
- **Wrap-around Mode**: When enabled, switching from the last desktop loops back to the first.
- **Ping-pong Mode**: When enabled, switching desktops alternates between moving forward and backward.
- **Dynamic Desktop Detection**: Automatically detects the number of desktops and the current desktop from the Windows registry.

## Installation
1. Install [AutoHotkey v2](https://www.autohotkey.com/download/).
2. Download the script (`VDS.ahk`).
3. Double-click the script to run it.

## Usage
- **Switch to Next Desktop**: Press `Win + Ctrl + Tab`.
- **Switch to Specific Desktop**: Press `Win + 1` to `Win + 9` (for desktops 1 through 9).
- **Toggle Wrap-around Mode or Ping-pong Mode**: Press `Win + Alt + Tab`.

## Credits
This script is inspired by and builds upon the work of the following resources and authors:

- [Computer Hope: Windows Desktop Switcher Tip](https://www.computerhope.com/tips/tip224.htm)
- [pmb6tz: Windows Desktop Switcher](https://github.com/pmb6tz/windows-desktop-switcher)

# License
This project is open-source and available under the MIT License. Feel free to modify and distribute it as needed.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
