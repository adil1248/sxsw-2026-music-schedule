[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/adil1248/sxsw-2026-music-schedule?style=social)](https://github.com/adil1248/sxsw-2026-music-schedule/stargazers)
[![Forks](https://img.shields.io/github/forks/adil1248/sxsw-2026-music-schedule?style=social)](https://github.com/adil1248/sxsw-2026-music-schedule/network/members)

# 🎸 SXSW 2026 Music Schedule — Interactive Gantt App
[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-adil1248.github.io-blue)](https://adil1248.github.io/sxsw-2026-music-schedule/)

A fan-made interactive schedule viewer for **SXSW 2026** (March 12–18, Austin TX). Browse all ~800+ acts across all venues in a color-coded Gantt chart, filter by genre, build your personal schedule, and hear 30-second song previews — all in a single HTML file you can run locally with no install required.

## 🚀 How to Use

### 🌐 Option 0: Use it Live (No Download Needed!)

**[https://adil1248.github.io/sxsw-2026-music-schedule/](https://adil1248.github.io/sxsw-2026-music-schedule/)**

Open in any browser — no download, no install, works instantly.

### Option 1: Download & Open (Easiest)
1. Download `SXSW-2026-Schedule-by-Genre.html` from this repo
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. That's it — no server, no install, no internet required after download

### Option 2: Use the JSX Source
The `SXSW-Schedule-by-Genre.jsx` file contains the full React source code if you want to modify or extend it.

## ✨ Features

- **Full Gantt Chart** — All ~800 acts across all SXSW venues, laid out on a timeline from 11am to 2am+
- **7 Days** — Thu Mar 12 through Wed Mar 18, switchable with one click
- **Genre Color Coding** — 11 genre categories (Rock/Indie, Hip-Hop/Rap, Pop, Electronic/DJ, Latin/Cumbia, Country/Americana, Folk/Singer-Songwriter, R&B/Soul, Punk/Metal, Jazz/Classical, Psych/Experimental) each with a distinct color
- **Genre Filters** — Click any genre badge to show/hide that genre on the chart
- **Search** — Search by artist name, venue, or presenter/showcase
- **30-Second Song Previews** — Hover over any act for 1.2 seconds and a preview panel pops up with a Spotify/Deezer audio preview (where available)
- **Personal Schedule Builder** — Click any act to add it to your saved schedule.
- - **Venue District Grouping** — Venues organized by Austin districts (Red River, Dirty Sixth, etc.) for better navigation
  - - **Live Wednesday Updates** — Latest Wednesday lineup additions and schedule changes
    - - **Bug Fixes** — Performance improvements and interface enhancements Acts highlight in gold when saved
- **My Schedule View** — Switch to a clean list view of all your saved acts sorted by day/time
- **Print to PDF** — Export your personal schedule as a printable PDF
- **Links** — Each act links to YouTube, Spotify, and the official SXSW schedule page

## 📁 Files

| File | Description |
|------|-------------|
| `SXSW-2026-Schedule-by-Genre.html` | **Download this** — standalone, works by opening in browser |
| `SXSW-Schedule-by-Genre.jsx` | React JSX source code for developers |

## 🎯 Tips

- **Hover** over an act for ~1 second to get the full details panel with music preview
- **Click** an act to add/remove it from your personal schedule
- Use **genre filters** to declutter — great for finding all Hip-Hop or Latin acts across venues
- Use the **search bar** to find a specific artist or showcase (e.g. search "British Music Embassy" or "Gogol Bordello")
- The **My Schedule** button shows your saved acts in a clean list — use Print PDF to save it
- Zoom controls let you expand the timeline for crowded time slots

## 📊 Data

Schedule data sourced from [schedule.sxsw.com](https://schedule.sxsw.com). Covers the full official SXSW 2026 music programming across all venues, Thu Mar 12 – Wed Mar 18.

## 🛠️ Tech Stack

- React 18 (loaded via CDN, no build step needed)
- Babel standalone (for JSX in-browser compilation)
- IBM Plex Mono font
- Deezer API + iTunes API for audio previews
- Pure CSS animations for the audio visualizer

---

*Not affiliated with SXSW. Fan-made tool for attendees.*


## 🤝 Contributing

Contributions are welcome! Whether you want to fix a bug, update schedule data, or add a new feature:

- 📖 Read the [Contributing Guide](CONTRIBUTING.md)
- 🐛 [Report a bug](../../issues/new?template=bug_report.md)
- ✨ [Request a feature](../../issues/new?template=feature_request.md)
- 🍴 Fork the repo, make your changes, and open a Pull Request

## ⭐ Show Your Support

If this helped you plan your SXSW week, give it a star — it helps others find it!

[![Star this repo](https://img.shields.io/github/stars/adil1248/sxsw-2026-music-schedule?style=social)](https://github.com/adil1248/sxsw-2026-music-schedule)
