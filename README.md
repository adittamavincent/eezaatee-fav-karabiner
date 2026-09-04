# Favorite Karabiner Configuration (`eezaatee-fav-karabiner`)

Personal Karabiner-Elements configuration file (`karabiner.json`) optimized for macOS navigation and custom key bindings.

## Features

- **Semicolon (`;`) Dual-Role Key**:
  - **Tap (press & release)**: Types `;` normally (or `:` with Shift).
  - **Hold down**: Activates the VIM navigation layer.
- **VIM Arrow Keys** (Hold `;`):
  - `; + H` → Left Arrow
  - `; + J` → Down Arrow
  - `; + K` → Up Arrow
  - `; + L` → Right Arrow
- **Natural macOS Modifiers Support**:
  - **Home / End**: `; + Cmd + H` (Line Start) & `; + Cmd + L` (Line End)
  - **Top / Bottom**: `; + Cmd + K` (Document Top) & `; + Cmd + J` (Document Bottom)
  - **Word Navigation**: `; + Option + H` (Previous Word) & `; + Option + L` (Next Word)
  - **Paragraph Navigation**: `; + Option + K` (Previous Paragraph) & `; + Option + J` (Next Paragraph)
  - **Text Selection**: Combine any of the above with `Shift` (e.g. `; + Shift + HJKL`, `; + Cmd + Shift + H/L`)

## Installation

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/) on macOS.
2. Copy `karabiner.json` to your Karabiner configuration directory:

```bash
cp karabiner.json ~/.config/karabiner/karabiner.json
```

3. Karabiner-Elements will automatically detect and apply the configuration.
