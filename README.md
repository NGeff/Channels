# Channels

Free live TV channels — watch Band, Globo, Record, and SBT directly in your browser.

[![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)

## Description

A simple collection of live TV channel pages. Each channel has its own folder with a standalone `index.html` that loads the stream directly. No server is required.

## Channels

| Channel | Folder |
|---------|--------|
| Band | `band/` |
| Globo | `globo/` |
| Record | `record/` |
| SBT | `sbt/` |

## Usage

Open any channel's `index.html` in your browser:

```bash
open Channels/band/index.html
```

Or serve the folder with any static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/band/`.

## Project Structure

```
Channels/
├── band/
│   └── index.html
├── globo/
│   └── index.html
├── record/
│   └── index.html
├── sbt/
│   └── index.html
└── README.md
```

## License

MIT © NGeff
