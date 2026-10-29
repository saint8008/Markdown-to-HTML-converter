# Markdown to HTML Converter

A lightweight, client-side Markdown to HTML converter built with vanilla JavaScript, HTML, and CSS. No dependencies, no build step—just open and use.

## 📖 Overview

This project provides a simple, fast, and fully client-side tool for converting Markdown text into HTML. It runs entirely in the browser, so your content never leaves your device.

## ✨ Features

- **Real-time conversion** — See HTML output as you type
- **Zero dependencies** — Pure vanilla JavaScript, HTML, and CSS
- **Live preview** — Rendered HTML preview alongside the source
- **Syntax support** for:
  - Headers (`#` through `######`)
  - Bold (`**text**`) and italic (`*text*`)
  - Strikethrough (`~~text~~`)
  - Links (`[text](url)`) and images (`![alt](url)`)
  - Ordered and unordered lists
  - Blockquotes (`>`)
  - Inline code and fenced code blocks
  - Horizontal rules (`---`)
  - Tables
- **Copy & download** — Copy HTML to clipboard or download as a `.html` file
- **Responsive design** — Works on desktop and mobile
- **Dark mode toggle** — Comfortable editing day or night

## 🚀 Getting Started

### Prerequisites

A modern web browser. That's it.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/markdown-to-html.git


markdown-to-html/
├── index.html      # Main HTML interface
├── style.css       # Styling and layout
├── js/
│   ├── main.js     # App logic and event handling
│   └── parser.js   # Markdown parsing logic
└── README.md