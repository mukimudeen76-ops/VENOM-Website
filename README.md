# VENOM — Download (3D)

Simple download page for the **VENOM AI Voice Assistant** (Android APK + Windows EXE).

## How it works

- **Fully static** — HTML/CSS/JS, no build step, deployed to GitHub Pages.
- **Auto-updating** — the page fetches the latest release from GitHub Releases every 60 seconds, so every time a new release is published the download buttons, version badges and release notes update **automatically**. No manual website edits ever needed.
- Download links point straight at the official GitHub release assets (APK + EXE).

## Deploy

Push to `main` → GitHub Actions deploys to GitHub Pages automatically
(see `.github/workflows/deploy.yml`).

Site URL: `https://mukimudeen76-ops.github.io/VENOM-Website/`
