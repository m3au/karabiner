# Windows-style Keyboard Configuration for macOS 🎯

This repository contains my personal Karabiner Elements configuration that makes macOS keyboard shortcuts behave more like Windows, with additional German character support.

## Features 🌟

### Windows-style Shortcuts
- Common Windows shortcuts (Ctrl+C, Ctrl+V, etc.) mapped to macOS equivalents
- Text editing shortcuts (Home, End, etc.)
- Navigation shortcuts (Ctrl+Arrow keys)
- Browser-specific shortcuts (Ctrl+L, Ctrl+R)
- Application control (Alt+F4 → Cmd+Q)

### Special German Character Support
Using Caps Lock as a modifier key:
- Caps Lock + a/o/u → ä/ö/ü
- Caps Lock + Shift + a/o/u → Ä/Ö/Ü
- Caps Lock + s → ß

### Application-Specific Rules
- Finder-specific shortcuts (F2 for rename, Return for open)
- Browser-specific URL and reload shortcuts
- Terminal-aware modifications

## Prerequisites 📋

- macOS (tested on Sonoma)
- [Karabiner Elements](https://karabiner-elements.pqrs.org/)

## Installation 🚀

1. Install Karabiner Elements from their [official website](https://karabiner-elements.pqrs.org/)
2. Download the `karabiner.json` file from this repository
3. Place it in `~/.config/karabiner/`
 ```bash
 # Backup your existing config (if any)
 cp ~/.config/karabiner/karabiner.json ~/.config/karabiner/karabiner.json.backup
 
 # Copy new config
 cp karabiner.json ~/.config/karabiner/
 ```

## Keyboard Profiles 🎹

### Profile: 🐈‍⬛ (Main Profile)
- Full Windows-style mappings
- German character support
- Application-specific rules

### Profile: Zero
- Clean profile without modifications
- Useful for troubleshooting

## Key Modifications Overview ⌨️

### Basic Windows Shortcuts
- `Ctrl + C/V/X` → Copy/Paste/Cut
- `Ctrl + Z/Y` → Undo/Redo
- `Ctrl + A/B/I` → Select All/Bold/Italic
- `Ctrl + S/N/W` → Save/New/Close
- `Alt + F4` → Quit Application

### Navigation
- `Home/End` → Start/End of line
- `Ctrl + Home/End` → Start/End of document
- `Ctrl + Left/Right` → Word-by-word movement
- `Ctrl + Up/Down` → Line movement

### Special Functions
- `Ctrl + Esc` → Launchpad
- `Ctrl + Shift + Esc` → Activity Monitor
- `Cmd + L` → Lock screen

### German Characters (with Caps Lock)
```
Caps Lock + a → ä    Caps Lock + Shift + a → Ä
Caps Lock + o → ö    Caps Lock + Shift + o → Ö
Caps Lock + u → ü    Caps Lock + Shift + u → Ü
Caps Lock + s → ß
```

## Contributing 🤝

Feel free to submit issues and enhancement requests!

## License 📝

MIT License - Feel free to use and modify as needed.

## Acknowledgments 🙏

- [Karabiner Elements](https://karabiner-elements.pqrs.org/) team for their amazing tool
- Windows users who helped test and refine these mappings
