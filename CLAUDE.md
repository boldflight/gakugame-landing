# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static landing page for the Manuscript Bible app, hosted via GitHub Pages at gakugame.app.

## Development

No build process required. Open `index.html` directly in a browser or use any local server:

```bash
python3 -m http.server 8000
```

## Structure

- `index.html` - Single-page landing with App Store link, hero image, and Ko-fi donation widget
- `css/styles.css` - CSS using custom properties for theming (--textColor, --backgroundColor, --appColor)
- `images/` - Hero screenshots, App Store badge, and favicon assets
- `CNAME` - GitHub Pages custom domain configuration (gakugame.app)

## External Dependencies

- TelemetryDeck analytics (loaded via CDN)
- Ko-fi donation widget overlay (loaded via CDN)
