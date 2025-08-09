# macOS Shortcuts

This repository contains a collection of custom macOS shortcuts and key mappings for use with Karabiner-Elements or similar key remapping tools.

## Shortcuts Overview

### 🎯 Mission Control
- **File**: `f3.json`
- **Key**: F3
- **Action**: Opens Mission Control
- **Description**: Quick access to Mission Control for managing desktops and windows

### 💡 Keyboard Brightness Control
- **File**: `keyboard-brightness.json`
- **Keys**: 
  - F5: Decrease keyboard backlight brightness
  - F6: Increase keyboard backlight brightness
- **Action**: Controls the backlight brightness of your MacBook's keyboard

### 🖥️ System Control
- **File**: `shut-down.json`
- **Key**: Control + Option + S
- **Action**: Shuts down the Mac
- **Description**: Quick shutdown shortcut

- **File**: `restart.json`
- **Key**: Control + Option + R
- **Action**: Restarts the Mac
- **Description**: Quick restart shortcut

## Installation

1. **Install Karabiner-Elements** (if not already installed):
   - Download from: https://karabiner-elements.pqrs.org/
   - Or install via Homebrew: `brew install --cask karabiner-elements`

2. **Import Shortcuts**:
   - Open Karabiner-Elements
   - Go to "Simple Modifications" tab
   - Click the "+" button to add a new rule
   - Select the desired shortcut file
   - Enable the rule

## File Format

All shortcut files use the Karabiner-Elements JSON format with the following structure:

```json
{
  "description": "Shortcut Description",
  "manipulators": [
    {
      "from": {
        "key_code": "key_name",
        "modifiers": {
          "mandatory": ["modifier1", "modifier2"],
          "optional": ["any"]
        }
      },
      "to": [
        {
          "key_code": "action_name"
        }
      ],
      "type": "basic"
    }
  ]
}
```

## Requirements

- macOS 10.12 or later
- Karabiner-Elements
- Administrator privileges for system-level shortcuts

## Notes

- Some shortcuts may require granting accessibility permissions to Karabiner-Elements
- System shortcuts (shutdown/restart) use shell commands and may require additional permissions
- Keyboard brightness shortcuts work on MacBooks with backlit keyboards

## Contributing

Feel free to add more shortcuts or modify existing ones. Each shortcut should be in its own JSON file with a descriptive filename and clear documentation.
