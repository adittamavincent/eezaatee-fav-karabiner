# Favorite Karabiner Configuration (`eezaatee-fav-karabiner`)

Personal Karabiner-Elements configuration file (`karabiner.json`) optimized for macOS navigation and custom key bindings.

## Features

- **Right Command VIM Layer**: Use `Right Command` held down as a modifier layer for VIM navigation:
  - `Right Cmd + H` → Left Arrow
  - `Right Cmd + J` → Down Arrow
  - `Right Cmd + K` → Up Arrow
  - `Right Cmd + L` → Right Arrow
- **VIM Navigation Shortcuts**:
  - `Right Cmd + Left Cmd + H` → `Ctrl + A` (Beginning of line)
  - `Right Cmd + Left Cmd + L` → `Ctrl + E` (End of line)
  - `Right Cmd + Left Cmd + J` → `Cmd + Down` (Bottom of document)
  - `Right Cmd + Left Cmd + K` → `Cmd + Up` (Top of document)

## Installation

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/) on macOS.
2. Copy `karabiner.json` to your Karabiner configuration directory:

```bash
cp karabiner.json ~/.config/karabiner/karabiner.json
```

3. Karabiner-Elements will automatically detect and apply the configuration.
