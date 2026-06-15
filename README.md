# Markdown to PDF Studio

> A premium, creamy-themed Markdown editor with live preview and PDF export. Built for bilingual academic note-taking with LaTeX math, Mermaid diagrams, and syntax highlighting.

## Features

### Editor
- Real-time split-pane Markdown editing with live preview
- Toolbar shortcuts: bold, italic, heading, blockquote, table, code block, math equation, mermaid diagram
- Drag-and-drop document reordering in the sidebar explorer
- Multi-document management with local storage persistence
- Import/export Markdown files (.md, .txt)

### Rendering
- **LaTeX Math** — KaTeX-powered inline ($...$) and block ($$...$$) equation rendering
- **Mermaid Diagrams** — Flowcharts, mindmaps, and sequence diagrams
- **Syntax Highlighting** — Highlight.js with support for Python, JavaScript, C++
- **GFM Tables** — GitHub-flavored Markdown table support
- **Task Lists** — Checkbox task lists with accent styling
- **Subscript/Superscript** — H~2~O and m^2^ notation
- **Text Highlighting** — ==highlighted text== syntax

### PDF Export
- Multi-page PDF generation via html2pdf.js
- A4 and Letter page sizes with configurable margins (5mm–20mm)
- Crisp 2.5x rendering scale for print quality
- CSS page-break rules for clean multi-page output

### UI/UX
- **Creamy Light Mode** — Warm sand aesthetic with golden amber accents
- **Responsive Design** — Desktop split-pane, mobile tab switching
- **Theme Accents** — Amber, Cocoa, Sage, Rose color options
- **Typography Toggle** — Modern Sans (Outfit) or Academic Serif (Lora)
- **Collapsible Sidebar** — Document explorer with mobile slide-out drawer
- **Custom Modal System** — Rename, delete, and create document dialogs

## Quick Start

1. Open `index.html` in any modern browser
2. Start typing Markdown in the left editor panel
3. See live preview on the right
4. Click **Download PDF** to export

No build step. No server required. Single HTML file.

## Tech Stack

| Library | Purpose |
|---------|---------|
| [Tailwind CSS](https://tailwindcss.com/) | Responsive layout & utility classes |
| [marked.js](https://marked.js.org/) | Markdown to HTML compilation |
| [KaTeX](https://katex.org/) | LaTeX math formula rendering |
| [Mermaid.js](https://mermaid.js.org/) | Diagram & flowchart generation |
| [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) | HTML to PDF multi-page export |
| [Highlight.js](https://highlightjs.org/) | Code syntax highlighting |
| [Font Awesome](https://fontawesome.com/) | UI icons |
| [Google Fonts](https://fonts.google.com/) | Outfit, Sora, Lora, Fira Code, Noto Sans Devanagari |

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Confirm modal | Enter |
| Cancel modal | Escape |

## File Structure

```
index.html          # Complete single-file application
README.md           # This file
```

## License

MIT
