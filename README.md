# Malayalam GK Quiz Website

This repository hosts a simple Malayalam General Knowledge (GK) quiz website, perfect for Kerala PSC exam prep and casual learning. It features interactive questions loaded from a JSON data file.

## Quick Start
- **Live Demo**: The site was hosted at https://malayalamgk.free.nf (InfinityFree hosting), but it's currently offline beacuse Domain suspended. Fork this repo to host your own copy.
  
**Files**:
  | File | Purpose |
  |------|---------|
  | `gk.json` | Contains GK questions in Malayalam (Q&A format for quizzes). |
  | `index.html` | Main webpage with quiz interface and JavaScript logic. |

## Features
- Loads questions dynamically from `gk.json`.
- Supports multiple-choice quizzes focused on Kerala GK topics.
- Lightweight, mobile-friendly design for easy access.
- No backend needed—runs entirely in the browser.

## Local Setup
1. Clone or download the repo.
2. Open `index.html` in any browser.
3. Questions load instantly from `gk.json`. No server required.

## Hosting
- **Recommended**: Use free hosts like GitHub Pages, Netlify, or Vercel. Upload files and deploy in minutes.
- **InfinityFree Note**: Previous hosting at malayalamgk.free.nf is down. Re-upload files there or switch providers.

## Contributing
Add new questions to `gk.json` (JSON array format: `[{"q": "...", "a": [...], "c": "..."}]`). Test locally before pushing.
