# RevoHuman project page

Static research website based on commit `911d070`, with an opening video.
No build step or package installation is required.

## Preview

Run from this repository:

```bash
python3 -m http.server 8766 --bind 127.0.0.1
```

Open http://127.0.0.1:8766.
Only the externally hosted opening video requires an internet connection.
The nine demonstration clips are served locally from `figs/`.

## Files

- `index.html`: page content, page styles, and the opening video URL.
- `figs/`: page images and nine demonstration MP4s.
- `videos/`: original shot-list documentation, not hosted video files.
- `vendor/`: local Lucide runtime dependency with license.
- `AGENTS.md`: branch and submission rules.

There are no generated bundles, duplicate encoded models, or export/build tools.
`Latex-template/` is not a website dependency and is excluded from Git.

## Features

The opening video streams from https://8.163.108.245/videos/preview.mp4.
It is not stored in this repository. The media server needs a valid HTTPS
certificate and available bandwidth; the website does not re-encode the video.

Figure 1 is currently omitted from the webpage. The earlier interactive 3D
viewer and its runtime have been removed pending an updated model.

## Publishing

GitHub Pages can serve the repository root directly from the `main` branch.

Demonstration videos follow the Abstract: six data-collection sessions and
three signal/replay clips. Timeline alignment remains a placeholder. The
unavailable overview section has been removed. The DATA button links to the
HumanDex dataset release at https://github.com/zuozuojia/RevoHuman/releases/tag/data-20260925.
