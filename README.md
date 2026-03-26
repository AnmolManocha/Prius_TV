<h1 align="center">Prius TV</h1>

<p align="center">
  Digital signage for commercial properties — built for the lobby, tuned for the wall.
</p>

<p align="center">
  <a href="#screenshots">Screenshots</a> ·
  <a href="#download">Download</a> ·
  <a href="#overview">Overview</a> ·
  <a href="#highlights">Highlights</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/orientation-Landscape-1e3a5f?style=flat-square" alt="Landscape" />
  <img src="https://img.shields.io/badge/runtime-Expo%20%2F%20React%20Native-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo / React Native" />
</p>

---

## Overview

**Prius TV** is a full-screen, landscape Android experience for **Prius Platinum** at **D3, District Centre Saket, New Delhi**. It cycles through branded welcome content, building directories, live environmental and weather context, and commercial listings — optimized for readability from across a lobby or reception area.

The on-device UI uses a deep navy palette, high-contrast type, and restrained red accents on brand moments (for example the accent on “Prius”), aligned with property signage.

---

## Highlights

| Area | What you get |
|------|----------------|
| **Welcome** | Property name, location line, and background treatment suited to large displays |
| **Awareness** | Time-of-day clock and location-aware weather in the header |
| **Directory** | Tenant and contact information surfaced for visitors |
| **Air quality** | Environmental readout for indoor awareness |
| **Market & notices** | Rotating commercial and announcement surfaces when content is available |
| **Operations** | Display stays awake; timed rotation between screens for passive signage |

---

## Screenshots

| File | Screen |
|------|--------|
| `welcome.png` | Welcome / landing |
| `directory.png` | Building directory |
| `air-quality.png` | Air quality (AQI) |
| `market.png` | Market / listings |
| `notices.png` | Notices / announcements *(only if you ship this surface)* |

<img width="1201" height="706" alt="Screenshot 2026-03-27 at 2 47 01 AM" src="https://github.com/user-attachments/assets/b5664f98-40d3-4d9c-a980-d8b2af736561" />
<img width="1201" height="706" alt="Screenshot 2026-03-27 at 2 43 18 AM" src="https://github.com/user-attachments/assets/ebf9036d-8b88-4131-b322-58c1d7678497" />
<img width="1201" height="706" alt="Screenshot 2026-03-27 at 2 43 43 AM" src="https://github.com/user-attachments/assets/d4525c3e-306b-42a4-ac39-d58ae7f3e7f1" />
<img width="1201" height="706" alt="Screenshot 2026-03-27 at 2 43 54 AM" src="https://github.com/user-attachments/assets/ead0232d-f55c-49e8-a4eb-ab1c5ba43fa4" />
<img width="1201" height="706" alt="Screenshot 2026-03-27 at 2 45 33 AM" src="https://github.com/user-attachments/assets/bed94497-f849-4da1-b33b-88541b11d735" />


### Welcome

<p align="center">
  <img src="https://github.com/user-attachments/assets/911d9f12-33be-43f5-9556-261dcf078fb5" alt="Prius TV welcome screen — WELCOME TO PRIUS PLATINUM, D3 District Centre Saket, with logo, date, time, and weather for New Delhi" width="100%" />
</p>

### Directory, air quality, market, notices

After you capture each screen, save it with the filename from the table above and drop it next to `welcome.png`. Then add one image block per screen (copy the Welcome block and change the `src` and `alt` text), or use a single row of thumbnails:

```markdown
<p align="center">
  <img src="./assets/screenshots/directory.png" alt="Directory" width="49%" />
  <img src="./assets/screenshots/air-quality.png" alt="Air quality" width="49%" />
</p>
```

Until those files exist, leave this section as-is so the README does not show broken images on GitHub.

---

## Download

This portfolio repository ships **screenshots and release binaries only** — no application source code.

1. Open **Releases** on your GitHub repo:  
   `https://github.com/AnmolManocha/Prius_TV/releases/latest`
2. Download the latest **`.apk`** from the release assets.
3. On the Android device, allow install from your browser or files app if prompted (“Install unknown apps”).
4. Open the APK and finish installation.
5. Run on a fixed tablet or TV box in **landscape**; layouts are tuned for wide aspect ratios.

---

## Tech (portfolio summary)

- **Expo** and **React Native** for a single Android deliverable with native performance on lobby hardware.
- **TypeScript** for maintainable UI and data flow.
- **Content and data** wired through APIs and a headless CMS where appropriate, so copy and listings can evolve without rebuilding for every text change (implementation detail available under NDA for client engagements).

---

## Legal & branding

Property names, logos, and photography in screenshots belong to their respective owners. This repository is intended **only for portfolio demonstration** and does **not** include private source, credentials, or environment configuration.

---

<p align="center">
  <sub>Portfolio — Prius Platinum · D3, District Centre Saket, New Delhi</sub>
</p>
