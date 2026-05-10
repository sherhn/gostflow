# GostFlow – GOST Flowchart Builder

**Live:** [gostflow.sherhn.space](https://gostflow.sherhn.space/)

A free, browser-based flowchart editor for creating algorithm diagrams that comply with the Russian standard **GOST 19.701-90** (equivalent to ISO 5807). No registration, no installation – just open and start drawing.

## Features

- **GOST-compliant shapes** – Start/End, Process, Decision, Input/Output, Predefined Process, Loop, Document, Manual Operation, Display, and more
- **Custom polygon shapes** – Draw freeform figures with editable vertices
- **Multi-sheet support** – Organise complex diagrams across multiple named sheets
- **Export** – Download your diagram as SVG or JSON
- **Import** – Load previously saved JSON diagrams
- **Dark & Light themes** – Switch between dark mode and a classic GOST paper look
- **Undo / Redo** – Full history with keyboard shortcuts (`Ctrl+Z` / `Ctrl+Y`)
- **Zoom & Fit** – Zoom in/out and auto-fit the diagram to the viewport

## Getting Started

The application is a single HTML file with no build step required.

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Drag shapes from the left panel onto the canvas and connect them with edges.

To deploy, simply host `index.html` (and the `/images` folder containing `favicon.svg`) on any static file server or CDN.

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Delete` / `Backspace` | Delete selected element |
| `Ctrl+A` | Select all |
| `Scroll` | Zoom |
| `Space + Drag` | Pan canvas |

## Standard Reference

Shapes follow **GOST 19.701-90 "Schemes of algorithms, programs, data and systems"**, the Russian national standard for flowcharts derived from ISO 5807:1985.

## License

See [LICENSE](LICENSE).
