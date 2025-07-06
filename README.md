# mac-shortcuts

A collection of custom macOS keyboard shortcuts for use with tools like Karabiner-Elements.

## Shortcuts

This repository contains JSON configuration files for the following shortcuts:

- **Keyboard Brightness** ([shortcuts/keyboard-brightness.json](shortcuts/keyboard-brightness.json))
  - `F5`: Decrease keyboard backlight brightness
  - `F6`: Increase keyboard backlight brightness

- **Restart** ([shortcuts/restart.json](shortcuts/restart.json))
  - `Control + Option + R`: Restart the Mac

- **Shut Down** ([shortcuts/shut-down.json](shortcuts/shut-down.json))
  - `Control + Option + S`: Shut down the Mac

## Usage

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/).
2. Copy the desired JSON files from the `shortcuts/` directory into your Karabiner-Elements configuration folder (usually `~/.config/karabiner/assets/complex_modifications/`).
3. Open Karabiner-Elements and add the imported rules from the "Complex Modifications" tab.

## License