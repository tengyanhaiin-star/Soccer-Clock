# ⚽ Soccer Clock

A football-themed analog clock built with HTML5 Canvas, designed for both desktop and iPhone (iOS Safari).

## Preview

A real-time analog clock styled like a football pitch, featuring:
- Green grass field with stripe texture and gold border
- Hour, minute, and second hands — with a ⚽ soccer ball counterweight on the second hand
- 12 clock numerals in Alatsi font
- A scoreboard panel that randomly displays two teams from the 48-nation 2026 international football tournament, switching every minute
- Live date display at the bottom
- Fully responsive — scales to fit any screen size
- iPhone / iOS Safari compatible

## Features

- **Pure HTML/CSS/JS** — single file, no dependencies, no build step
- **Responsive scaling** — adapts to any viewport via `visualViewport` API
- **iOS optimised** — `viewport-fit=cover`, safe area insets, pinch-zoom disabled, `dvh` units
- **High-DPI canvas** — sharp rendering on Retina / Pro Motion displays (DPR capped at 3×)
- **Random team display** — 48 teams with national flags (via [flagcdn.com](https://flagcdn.com)) and FIFA-standard 3-letter codes, shuffled every minute
- **Google Fonts** — Alatsi (clock numerals), DM Mono (UI text)

## Usage

Download `soccer_clock.html` and open it in any modern browser. No server required.

```
git clone https://github.com/tengyanhaiin-star/Soccer-Clock.git
open Soccer-Clock/soccer_clock.html
```

Or open directly on iPhone via Safari by hosting the file (e.g. GitHub Pages).

## GitHub Pages

You can enable GitHub Pages in the repository settings to host the clock online and open it on any device via URL.

## Credits

- National flag images: [flagcdn.com](https://flagcdn.com) (free to use)
- Fonts: [Google Fonts](https://fonts.google.com) — Alatsi, DM Mono

## Disclaimer

This project is an independent personal/educational work and is not affiliated with, endorsed by, or associated with FIFA or any football governing body. All team names and abbreviations are based on publicly available, internationally recognised country codes (ISO 3166-1).

## License

MIT — see [LICENSE](LICENSE)
