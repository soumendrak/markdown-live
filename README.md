<div align="center">

# Markdown Live Preview

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/markdown-live/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="10" y="20" width="58" height="106" rx="4" fill="#0d0d1a"/>
  <line x1="16" y1="28" x2="62" y2="28" stroke="#2a2a2a" stroke-width="2"/>
  <line x1="16" y1="34" x2="62" y2="34" stroke="#2a2a2a" stroke-width="2"/>
  <rect x="72" y="20" width="58" height="106" rx="4" fill="#0d0d1a"/>
  <text x="86" y="38" font-family="sans-serif" font-size="7" font-weight="bold" fill="#ff6b35">H1</text>
  <text x="86" y="48" font-family="sans-serif" font-size="6" fill="#f0ece4">Text</text>
  <text x="86" y="56" font-family="sans-serif" font-size="6" fill="#4caf7d">• list</text>
</svg>

**Split-view live markdown editor with a custom, zero-dependency parser.**

**Live:** [https://soumendrak.github.io/markdown-live/](https://soumendrak.github.io/markdown-live/)

</div>

---

## Features

- Split view: edit markdown on the left, preview rendered HTML on the right
- Built with a custom ~75-line markdown parser — no libraries
- Supports: h1-h6, bold, italic, links, lists, code blocks, blockquotes, HR
- Tab toggle: Split / Editor / Preview modes
- Copy rendered HTML to clipboard
- Default placeholder text demonstrating all supported formats
- Dark theme with orange accent (#ff6b35)

## How It Works

The custom parser processes text line-by-line using regex patterns for block-level elements (headers, blockquotes, code blocks, HR, list items), then inline elements (bold, italic, code, links). The preview pane uses `innerHTML` to render the parsed output. A debounced input listener (150ms) ensures smooth live updates without excessive re-parsing.

## Usage

1. Open `https://soumendrak.github.io/markdown-live/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/markdown-live.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
