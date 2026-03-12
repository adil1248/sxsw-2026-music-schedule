# Contributing to SXSW 2026 Music Schedule

Thanks for your interest in contributing! This is a fan-made project and all help is welcome — whether it's fixing a bug, improving the UI, correcting schedule data, or adding new features.

## Ways to Contribute

### 🐛 Report a Bug
- Open an [Issue](../../issues) with the label `bug`
- Include: what you expected, what happened, your browser/OS
- Screenshots are super helpful

### 🎵 Fix or Update Schedule Data
- The artist/venue/time data lives in the JSX file as a JavaScript array
- If you spot a wrong time, missing act, or wrong venue — open a PR with the fix
- Please link to a source (e.g. official SXSW schedule page)

### ✨ Suggest a Feature
- Open an [Issue](../../issues) with the label `enhancement`
- Describe the feature and why it would help attendees

### 🛠️ Submit a Pull Request
1. Fork the repo
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes in the JSX file (the HTML is auto-generated from it)
4. Test by opening the HTML in a browser
5. Submit a PR with a clear description of what changed and why

## Project Structure

```
sxsw-2026-music-schedule/
├── SXSW 2026 Schedule by Genre (2).html   # Standalone app — download & open this
├── SXSW Schedule by Genre (1).jsx         # React JSX source (edit this)
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

## Tech Notes for Developers

- The app uses **React 18** loaded via CDN + **Babel standalone** for in-browser JSX compilation — no build step required
- All data is hardcoded in the JSX as a `const acts = [...]` array
- Audio previews use the **Deezer API** and **iTunes API** — no API key needed
- The HTML file is a self-contained export of the JSX (copy the JSX into the `<script type="text/babel">` block)

## Code Style

- Keep it simple — this is a single-file app, readability > cleverness
- Use consistent formatting for act data objects
- Test in Chrome and Firefox before submitting

## Questions?

Open an issue and tag it `question`. Happy to help!

---
_Not affiliated with SXSW. Fan project._
