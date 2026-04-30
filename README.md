# framepath.

Digitalstudio aus München. Marketing-Site (single-page, no build step).

## Setup

```bash
npm install
npm run dev
```

Server läuft anschließend auf [http://localhost:3000](http://localhost:3000).

### Falls Node fehlt (macOS)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node
```

## Stack

- Eine `index.html` (HTML + eingebettetes CSS + JS)
- `live-server` als Dev-Server (Auto-Reload)
- Google Fonts CDN (Syne, Geist, Geist Mono, Instrument Serif)
- Kein Build, keine Frameworks
