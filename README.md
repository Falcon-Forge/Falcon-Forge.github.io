# Falcon Forge — Universal File Converter

[![Deploy to GitHub Pages](https://github.com/Falcon-Forge/Falcon-Forge.github.io/actions/workflows/static.yml/badge.svg)](https://github.com/Falcon-Forge/Falcon-Forge.github.io/actions/workflows/static.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A free, open-source file converter that runs entirely in your browser. Convert images, documents, videos, audio files, and archives instantly — no uploads required, 100% private.

🔗 **[Try it now → Falcon-Forge.github.io](https://falcon-forge.github.io)**

## ✨ Features

- **🖼️ Image Converter** — Convert between PNG, JPG, WebP, AVIF, GIF, BMP, ICO, and more
- **📄 Document Converter** — Transform TXT, HTML, Markdown, CSV, JSON to PDF and other formats
- **🎬 Video Converter** — Convert MP4 and WebM with resolution options (1080p, 720p, 480p)
- **🎵 Audio Converter** — Process WAV, MP3, OGG, FLAC, AAC files with bitrate control
- **📦 Archive Tools** — Create and extract ZIP files

### Additional Capabilities

- **Batch Processing** — Convert multiple files at once
- **Image Editing** — Resize, rotate, and flip images
- **Quality Control** — Adjust compression quality for optimal file size
- **Target Size Compression** — Compress images to a specific file size
- **Dark/Light Theme** — Choose your preferred viewing mode
- **Keyboard Shortcuts** — Efficient workflow with hotkeys
- **Accessibility** — Screen reader friendly with ARIA support

## 🔒 Privacy First

All file conversions happen **directly in your browser** using JavaScript. Your files:

- ❌ Never leave your device
- ❌ Are not uploaded to any server
- ❌ Are not stored or logged anywhere
- ✅ Stay completely private

## 📖 Usage

1. Visit [falcon-forge.github.io](https://falcon-forge.github.io)
2. Select a converter category (Images, Documents, Video, Audio, Archives)
3. Drag and drop your file(s) or click to browse
4. Choose your desired output format and settings
5. Click Convert and download your file

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `O` | Open file dialog |
| `Enter` | Convert file |
| `R` | Rotate image right |
| `Shift + R` | Rotate image left |
| `H` | Flip horizontal |
| `V` | Flip vertical |
| `T` | Toggle theme |
| `?` | Show shortcuts |
| `Esc` | Close dialogs |

## 🛠️ Supported Formats

### Images
| Input | Output |
|-------|--------|
| PNG, JPG, JPEG, GIF, BMP, WebP, TIFF, ICO, SVG | PNG, JPG, WebP, AVIF, GIF, BMP, ICO |

### Documents
| Input | Output |
|-------|--------|
| TXT, HTML, Markdown, CSV, JSON, XML | PDF, TXT, HTML, Markdown, CSV, JSON |

### Video
| Input | Output |
|-------|--------|
| MP4, WebM, AVI, MOV | MP4, WebM |

### Audio
| Input | Output |
|-------|--------|
| MP3, WAV, OGG, FLAC, AAC, M4A | WAV, OGG, WebM (audio) |

### Archives
| Input | Output |
|-------|--------|
| ZIP | Individual files (extract) |
| Any files | ZIP (create) |

## 🧰 Technology

Falcon Forge is built with:

- **Pure HTML/CSS/JavaScript** — No frameworks, no build process
- **[JSZip](https://stuk.github.io/jszip/)** — ZIP file creation and extraction
- **[PDF-lib](https://pdf-lib.js.org/)** — PDF generation
- **[jsPDF](https://github.com/parallax/jsPDF)** — Document to PDF conversion
- **Web APIs** — Canvas, MediaRecorder, AudioContext for media conversion

## 🚀 Local Development

Since this is a static site with no build process, you can run it locally with any web server:

```bash
# Clone the repository
git clone https://github.com/Falcon-Forge/Falcon-Forge.github.io.git
cd Falcon-Forge.github.io

# Serve with Python
python -m http.server 8000

# Or with Node.js
npx serve

# Or with PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions

- Add support for more file formats
- Improve conversion quality
- Add new image editing tools
- Enhance accessibility features
- Fix bugs and improve performance

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Icons designed with [Lucide](https://lucide.dev/)
- Fonts: [Space Mono](https://fonts.google.com/specimen/Space+Mono) and [Syne](https://fonts.google.com/specimen/Syne)
- Built with ❤️ for the open source community

---

<p align="center">
  <strong>Falcon Forge</strong> — Convert anything, privately.
</p>
