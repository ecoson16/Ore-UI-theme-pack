<!--
SPDX-FileCopyrightText: 2026 Nursultan Akim

SPDX-License-Identifier: CC0-1.0
-->

# Ore UI - Font (JetBrainsMono Nerd Font)

Every Ore UI stylesheet uses this font family:

```css
font-family: "JetBrainsMono Nerd Font", monospace;
```

The font files are not bundled in this repository. Download the official [JetBrainsMono Nerd Font archive](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip) from [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts). Extract the archive and install `JetBrainsMonoNerdFont-Regular.ttf`; install the bold and italic variants as desired.

## Installation

### Windows
1. Extract the archive.
2. Right-click the required `.ttf` files and choose **Install**.

### macOS
1. Extract the archive.
2. Open the required `.ttf` files in Font Book and click **Install**.

### Linux
1. Copy the required `.ttf` files into `~/.local/share/fonts/` (create the folder if needed).
2. Refresh the font cache:

   ```sh
   fc-cache -f
   ```

Restart Prism Launcher after installing the font. If the font is not detected, check that the installed font family is named **JetBrainsMono Nerd Font**.

The font and its patches are distributed by the Nerd Fonts project. Refer to the upstream release for the applicable font licenses.
