# MedVidU 2026 Workshop Website

Static website for the **Workshop on Medical Video Understanding (MedVidU)** at ECCV 2026.

## Files

- `index.html` — single-page site (Tailwind via CDN, no build step)
- `img/` — drop banner and organizer/speaker photos here
  - `banner.png` — hero background image
  - portrait images can replace the placeholder URLs in `index.html`

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploying to GitHub Pages

1. Push this folder to a repo (e.g. `medvidu.github.io` or any repo with Pages enabled)
2. Settings → Pages → Source: `main` branch, `/` root

## Sections marked TODO / placeholder

These sections are intentionally placeholders, ready to be filled in later:

- **Challenge** (`#challenge`) — submission instructions, evaluation protocol, prizes
- **Dataset** (`#dataset`) — HuggingFace link is commented out and ready to enable:
  ```html
  <!-- https://huggingface.co/datasets/MedVidBench -->
  ```
- **Leaderboard** (`#leaderboard`) — HuggingFace Space link is commented out and ready to enable:
  ```html
  <!-- https://huggingface.co/spaces/MedVidBench/leaderboard -->
  ```
- **Speakers** — both keynote speakers marked "Tentative"
- **Timeline dates** — currently "TBD (approx. July/August 2026)"
- **Organizer photos** — using `placehold.co` placeholders; replace `src` with real images

Search `placeholder-box`, `placehold.co`, or `TBD` in `index.html` to find spots to update.
