# SF Font Collection

A collection of high-quality fonts for development and design projects.

## Contents

This repository includes the following font families:

### San Francisco Font Family
- **San Francisco Compact** - A condensed variant optimized for tight spaces
- **San Francisco Mono** - A monospaced font perfect for code editors and terminals
- **San Francisco Pro** - Apple's system font, excellent for UI design and general text

## Installation

### macOS
1. Download the font files from the respective folders
2. Double-click each font file to open Font Book
3. Click "Install Font" for each file

### Windows
1. Download the font files
2. Right-click each font file and select "Install"
3. Or copy fonts to `C:\Windows\Fonts\`

### Linux
1. Download the font files
2. Copy fonts to `~/.local/share/fonts/` (user) or `/usr/share/fonts/` (system-wide)
3. Run `fc-cache -f -v` to refresh font cache

## Usage

### In Code Editors
Set San Francisco Mono as your editor font for optimal code readability:

```json
# VS Code settings.json
{
  "editor.fontFamily": "'SF Mono', Consolas, monospace"
}

# For UI text
{
  font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif;
}

# For code/monospace text
{
  font-family: 'SF Mono', 'Monaco', 'Consolas', monospace;
}

# For compact layouts
{
  font-family: 'SF Compact Display', sans-serif;
}
```
