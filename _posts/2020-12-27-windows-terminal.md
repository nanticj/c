---
title: Windows Terminal
tags:
  - windows
---

Windows Terminal is a new, modern, feature-rich, productive terminal application for command-line users.

# Installation
## Windows (administrative powershell)
```powershell
choco install microsoft-windows-terminal
```

# Settings
Windows Terminal > Settings
```json
"defaults":
{
  "colorScheme": "SolarizedLight",
  "cursorShape": "filledBox",
  "fontFace": "D2Coding",
  "fontSize": 12
}

"schemes": [
  {
    "name": "SolarizedLight",
    "background": "#fdf6e3",
    "foreground": "#657b83",
    "cursorColor": "#93a1a1",
    "selectionBackground": "#eee8d5",
    "brightBlack": "#002b36",
    "black": "#073642",
    "brightGreen": "#586e75",
    "brightYellow": "#657b83",
    "brightBlue": "#839496",
    "brightCyan": "#93a1a1",
    "white": "#eee8d5",
    "brightWhite": "#fdf6e3",
    "yellow": "#b58900",
    "brightRed": "#cb4b16",
    "red": "#dc322f",
    "purple": "#d33682",
    "brightPurple": "#6c71c4",
    "blue": "#268bd2",
    "cyan": "#2aa198",
    "green": "#859900"
  }
]
```

# References
- [Profile settings](https://aka.ms/terminal-profile-settings)
- [Color schemes](https://aka.ms/terminal-color-schemes)
- [Custom actions](https://aka.ms/terminal-keybindings)
- [Solarized](https://ethanschoonover.com/solarized/)
