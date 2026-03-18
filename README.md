# Calc\*on

A Sumlock-style running total calculator with memory recall chips. A dual scroll-wheel unit converter and fraction-aware calculator — built for people who work with various measurements every day. Designed with a bit of a 90s aesthetic, with a hope to bring a fun and tactile way to input measurements

App here: https://calcon.pages.dev/

---

## Features

**Converter**
- **Length** — inches ↔ centimeters, with fraction, half, and feet sub-info
- **Pixels** — inches or cm ↔ pixels at adjustable PPI (72–600)
- **Vol/Mass** — oz/lb ↔ ml/kg, with tablespoon, cup, pint, quart, gallon, and metric equivalents
- **Temp** — °F ↔ °C, with air, reference, and cook presets

**Calculator**
- Standard arithmetic with a fraction slider (1/32 increments)
- Memory bank — stores up to 8 values, tap to recall
- **SET IMPERIAL** / **SET METRIC** — sends calculator result directly to the converter

**Design**
- Light and Dark color modes
- Fully self-contained single HTML file — no server, no dependencies at runtime
- Works offline once loaded
- Responsive — full width on mobile, 55% centered column on desktop

---

## Keyboard Shortcuts

### Anywhere
| Key | Action |
|-----|--------|
| `C` | Toggle between Calculator and Converter |
| `W` | Cycle color themes (Light → Dark) |

### Converter (calculator closed)
| Key | Action |
|-----|--------|
| `→` | Next converter mode |
| `←` | Previous converter mode |
| `0–9` | Type digits into left wheel |
| `Backspace` | Remove last digit from left wheel |
| `Z` | Zero both wheels |

### Calculator
| Key | Action |
|-----|--------|
| `0–9`, `.` | Number input |
| `-` | Minus |
| `=` or `+` | Plus |
| `X` or `*` | Multiply |
| `/` | Divide |
| `Enter` | Equals |
| `Backspace` | Delete last digit |
| `Z` | Clear everything |
| `%` | Percent |
| `M` | Set Metric → switch to converter |
| `I` | Set Imperial → switch to converter |
| `Cmd/Ctrl + C` | Copy current result |

---

## Deployment

Calc\*on is a single `.html` file. Drop it anywhere — Cloudflare Pages, Netlify, or just open it locally in a browser. No build step required.

```
# Hosted
https://calcon.pages.dev/
```

---

## Built with

- Vanilla JS — no framework
- [Geist](https://fonts.google.com/specimen/Geist) via Google Fonts
- SVG scroll wheels with physics-based ridge animation
- Vibration API for haptic feedback on supported devices (Android Chrome)

---

## License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).  
You are free to use, modify, and distribute this software under the same license terms.

---

## Author

Christopher Cunningham  
[github.com/christophcunningham](https://github.com/christophcunningham)
