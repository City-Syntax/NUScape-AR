# NUScape-AR

**WebAR for NUS Campus Energy Data**

A no-download WebAR experience that surfaces real campus energy data through your phone camera. Point at any of the 20 supported building markers to instantly see energy breakdowns, building details, and a direct link to Google Maps — all running on-device in the browser.

🔗 **[Launch the experience →](https://nus-built-environment-web-ar.vercel.app/)**

---

![Landing page](readme1.png)

![AR experience](readme2.jpg)

---

## Features

- **Barcode marker tracking** — AR.js detects printed 4×4 BCH barcode markers and anchors A-Frame overlays onto them
- **Energy chart** — doughnut panel showing annual energy breakdown (Cooling / Equipment / Lighting) and monthly EUI
- **Daylight heatmap** — per-floor daylight simulation images with floor selector
- **Solar mat** — rooftop solar panel layout overlay
- **Building video tour** — campus building walkthrough videos
- **Maps panel** — building photo card linking to Google Maps

No backend, no app install — runs entirely on-device in the browser.

---

## Supported Buildings (20)

| Code | Building |
|------|----------|
| CELC | Centre for English Language Communication |
| E1 | Engineering Block E1 |
| E1A | Engineering Block E1A |
| E2 | Engineering Block E2 |
| E2A | Engineering Block E2A |
| E3 | Engineering Block E3 |
| E3A | Engineering Block E3A |
| E4 | Engineering Block E4 |
| E4A | Engineering Block E4A |
| E5 | Engineering Block E5 |
| E6 | Engineering Block E6 |
| E7 | Engineering Block E7 |
| E8 | Engineering Block E8 |
| EA | Engineering Auditorium |
| EW1 | Engineering Workshop 1 |
| IT | I³ Building |
| SDE1 | School of Design and Environment 1 |
| SDE2 | School of Design and Environment 2 |
| SDE3 | School of Design and Environment 3 |
| SDE4 | School of Design and Environment 4 (net-zero) |
| T-Lab | The Teaching Lab |

---

## Tech Stack

| Library | Purpose |
|---------|---------|
| [AR.js](https://ar-js-org.github.io/AR.js-Docs/) | Barcode marker tracking |
| [A-Frame 1.7.0](https://aframe.io) | 3D scene and AR overlay rendering |
| React + Vite | Landing page and building video tour |

---

*Built for NUS Department of the Built Environment · 2026*
