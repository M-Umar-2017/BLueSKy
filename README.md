# BlueSKy Icons

[![License: CC0 1.0 Universal](https://img.shields.io/badge/License-CC0_1.0_Universal-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/) [![Icons](https://img.shields.io/badge/Icons-8-0078d4.svg)](https://github.com/M-Umar-2017/BLueSKy) [![Formats](https://img.shields.io/badge/Formats-PNG%20%7C%20ICNS%20%7C%20ICO-0078d4.svg)](https://github.com/M-Umar-2017/BLueSKy) [![Resolution](https://img.shields.io/badge/Resolution-1024x1024-0078d4.svg)](https://github.com/M-Umar-2017/BLueSKy)

A **minimal, elegant collection of blue-themed icons** for your favorite development and creative applications: **Affinity, Blender, Chrome, Git, LibreSprite, PowerToys, VSCode, and Zed**. Each icon is meticulously designed with a cohesive sky-blue aesthetic, perfect for customizing your desktop, dock, or application launcher.

---

## Icon Gallery

| Application | Preview | File |
|-------------|---------|------|
| **Affinity** | ![Affinity Icon](.png%20Files/affinity-sky.png) | [`.png Files/affinity-sky.png`](.png%20Files/affinity-sky.png) |
| **Blender** | ![Blender Icon](.png%20Files/blender-sky.png) | [`.png Files/blender-sky.png`](.png%20Files/blender-sky.png) |
| **Chrome** | ![Chrome Icon](.png%20Files/chrome-sky.png) | [`.png Files/chrome-sky.png`](.png%20Files/chrome-sky.png) |
| **Git** | ![Git Icon](.png%20Files/git-sky.png) | [`.png Files/git-sky.png`](.png%20Files/git-sky.png) |
| **LibreSprite** | ![LibreSprite Icon](.png%20Files/libresprite-sky.png) | [`.png Files/libresprite-sky.png`](.png%20Files/libresprite-sky.png) |
| **PowerToys** | ![PowerToys Icon](.png%20Files/powertoys-sky.png) | [`.png Files/powertoys-sky.png`](.png%20Files/powertoys-sky.png) |
| **VSCode** | ![VSCode Icon](.png%20Files/vscode-sky.png) | [`.png Files/vscode-sky.png`](.png%20Files/vscode-sky.png) |
| **Zed** | ![Zed Icon](.png%20Files/zed-sky.png) | [`.png Files/zed-sky.png`](.png%20Files/zed-sky.png) |

---

## Features

- **Multiple Formats**: Available in PNG, ICNS (macOS), and ICO (Windows) formats
- **High Resolution**: 1024x1024 pixels (RGBA PNG format)
- **Consistent Style**: Unified blue-themed design language
- **Transparent Background**: Perfect for any theme or wallpaper
- **Lightweight**: Optimized file sizes without losing quality
- **Public Domain**: Free for personal and commercial use (CC0 1.0)

---

## Available Formats

This repository provides icons in three different formats for maximum compatibility:

| Format | Folder | Use Case | Platform |
|--------|--------|----------|----------|
| **PNG** | [`.png Files/`](.png%20Files/) | Original high-resolution | All platforms |
| **ICNS** | [`.icns Files/`](.icns%20Files/) | macOS native format | macOS |
| **ICO** | [`.ico Files/`](.ico%20Files/) | Windows native format | Windows |

---

## Usage

### Desktop Customization

#### Windows
1. Use the `.ico` files from the [`.ico Files/`](.ico%20Files/) folder
2. Right-click the shortcut -> Properties -> Change Icon -> Browse to the `.ico` file

#### macOS
1. Use the `.icns` files from the [`.icns Files/`](.icns%20Files/) folder
2. Apply via Get Info or use with your application bundle

#### Linux
1. Use the `.png` files from the [`.png Files/`](.png%20Files/) folder
2. Most desktop environments support PNG icons directly in `.local/share/applications/`

### Development Projects
- Use PNG files as app icons in your Electron, Flutter, or native applications
- Use ICNS files for macOS app bundles
- Use ICO files for Windows executables
- Include in documentation or README files
- Customize your IDE or editor themes

### Web & Design
- Perfect for favicons (use ICO or PNG format)
- Use in design mockups or presentations
- Create custom emoji for Discord/Slack

---

## File Structure

```
BLueSKy/
├── .icns Files/          # macOS ICNS format icons
│   ├── affinity-sky.icns
│   ├── blender-sky.icns
│   ├── chrome-sky.icns
│   ├── git-sky.icns
│   ├── libresprite-sky.icns
│   ├── powertoys-sky.icns
│   ├── vscode-sky.icns
│   └── zed-sky.icns
│
├── .ico Files/           # Windows ICO format icons
│   ├── affinity-sky.ico
│   ├── blender-sky.ico
│   ├── chrome-sky.ico
│   ├── git-sky.ico
│   ├── libresprite-sky.ico
│   ├── powertoys-sky.ico
│   ├── vscode-sky.ico
│   └── zed-sky.ico
│
├── .png Files/           # Original PNG format icons
│   ├── affinity-sky.png
│   ├── blender-sky.png
│   ├── chrome-sky.png
│   ├── git-sky.png
│   ├── libresprite-sky.png
│   ├── powertoys-sky.png
│   ├── vscode-sky.png
│   └── zed-sky.png
│
├── LICENSE
└── README.md
```

---

## Design Philosophy

Each icon maintains the essence of the original application while adopting a **cohesive blue color palette** that creates harmony across your entire workspace.

---

## License

This work is licensed under **CC0 1.0 Universal** (Public Domain).

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

**You are free to:**
- Share, copy, and redistribute the material in any medium or format
- Adapt, remix, transform, and build upon the material for any purpose
- Use for commercial purposes without attribution

**Without any restrictions.**

---

## Attribution

While not required by the CC0 license, attribution is always appreciated:

```markdown
Icons by [𝐌𝐀𝐃𝐄𝐂][M-Umar-2017](https://github.com/M-Umar-2017) from [BLueSKy](https://github.com/M-Umar-2017/BLueSKy) collection
```

---

## Tips

- **Batch Conversion**: Use tools like [ImageMagick](https://imagemagick.org/) to convert between formats:
  ```bash
  # PNG to ICO
  magick *.png -set icon:auto-resize 256,128,64,48,32,16 -colorspace sRGB icon.ico
  
  # PNG to ICNS (requires img2icns or similar)
  # Use macOS tools or online converters
  ```

- **Color Customization**: Use photo editing software to recolor the icons to match your theme

---

## Contributing

Found a bug or have a suggestion? Feel free to:
1. Open an issue on [GitHub Issues](https://github.com/M-Umar-2017/BLueSKy/issues)
2. Submit a pull request with your improvements
3. Request new icons for other applications

---

## Download

[Download Latest Release](https://github.com/M-Umar-2017/BLueSKy/archive/refs/heads/main.zip) | [View on GitHub](https://github.com/M-Umar-2017/BLueSKy)

---

<p align="center">
  Made with love by <a href="https://github.com/M-Umar-2017">𝐌𝐀𝐃𝐄𝐂</a> | 
  <a href="https://github.com/M-Umar-2017/BLueSKy">View Repository</a>
</p>

---

# Icon Display

<p align="center">
  <img src=".png Files/affinity-sky.png" alt="Affinity" width="128" height="128" />
  <img src=".png Files/blender-sky.png" alt="Blender" width="128" height="128" />
  <img src=".png Files/chrome-sky.png" alt="Chrome" width="128" height="128" />
  <img src=".png Files/git-sky.png" alt="Git" width="128" height="128" />
  <img src=".png Files/libresprite-sky.png" alt="LibreSprite" width="128" height="128" />
  <img src=".png Files/powertoys-sky.png" alt="PowerToys" width="128" height="128" />
  <img src=".png Files/vscode-sky.png" alt="VSCode" width="128" height="128" />
  <img src=".png Files/zed-sky.png" alt="Zed" width="128" height="128" />
</p>

<p align="center">
  <sub>8 Minimal Blue-Themed Icons | 3 Formats (PNG, ICNS, ICO) | CC0 1.0 Universal</sub>
</p>
