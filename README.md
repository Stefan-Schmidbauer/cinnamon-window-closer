# Window Closer - Cinnamon Applet

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Cinnamon 5.4+](https://img.shields.io/badge/Cinnamon-5.4%2B-brightgreen.svg)](https://github.com/linuxmint/cinnamon)

A Cinnamon desktop applet that lets you quickly close multiple windows from a visual overview.

![Window Closer](screenshot.png)

## Features

- Click the panel icon to open a fullscreen overlay with all open windows
- Each window is shown as a card with a **live thumbnail** preview, app icon, and title
- Click any card to **close that window** instantly
- The overlay stays open so you can close multiple windows in a row
- Cards turn red on hover to indicate which window will be closed
- Press **Esc** or click the dark background to dismiss the overlay

## Installation

### From source

```bash
git clone https://github.com/Stefan-Schmidbauer/cinnamon-window-closer.git
cd cinnamon-window-closer
cp -r window-closer@stefan-schmidbauer/files/window-closer@stefan-schmidbauer ~/.local/share/cinnamon/applets/
```

Then reload Cinnamon (**Alt+F2** > type `r` > Enter) and activate the applet:
1. Right-click the Cinnamon panel
2. Select **Applets**
3. Find **Window Closer** and enable it

## Uninstallation

```bash
rm -rf ~/.local/share/cinnamon/applets/window-closer@stefan-schmidbauer
```

Then reload Cinnamon (**Alt+F2** > type `r` > Enter).

## Requirements

- Linux Mint / Ubuntu with **Cinnamon 5.4+** desktop environment
- No external dependencies

## License

MIT License © 2026 Stefan Schmidbauer — see [LICENSE](LICENSE) for details. Built with [Claude Code](https://claude.ai/claude-code).
