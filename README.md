# Plugins by Dani Koenig

Download page for my free macOS plugins: One Shooter, Quad Shooter, Drift Station, Siren, Repetitor.

## Setup (GitHub Pages)

1. Create a new public repo, e.g. `danikoenig/plugins`, and upload `index.html`, `.nojekyll` and the `img` folder.
2. Settings > Pages > Source: "Deploy from a branch", Branch `main`, folder `/ (root)` > Save.
3. After about a minute the page is live at `https://danikoenig.github.io/plugins/`.

## How it updates

- Download buttons point to `releases/latest/download/<Name>-Installer.pkg`, so they always deliver the newest release.
- The version badge is read live from the GitHub API. The version in `index.html` is only the fallback.

## Editing

All plugin texts are in the `plugins` list at the bottom of `index.html`.
To show a 'Watch reel' button, put the YouTube Shorts ID into `reel:''` (e.g. `reel:'hZExpdoyzUo'`).
New screenshot: replace the file in `img/`.
