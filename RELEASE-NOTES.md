# Twig release notes

Newest first. Downloads: https://github.com/JKS-sys/twig-08-oct-2026-releases/releases/latest · https://ipconfig.co.network/twig

## Twig 1.0.3 — 12 Oct 2026

- **Publish to GitHub, GitLab, Bitbucket, Codeberg, Gitea, Forgejo, Azure DevOps, SourceForge or Radicle:** add an account once (a token, or your GitHub CLI sign-in), then create a **public or private** repository and push to it in one step. Pushing a repository that has no remote now offers this instead of an error.
- **Accounts:** Twig remembers your hosts and answers their HTTPS password prompts itself when your keychain has nothing — push and pull to GitLab, Bitbucket, Codeberg and the rest with no extra setup. Tokens stay on this computer.
- **New repository:** name, folder, README, a .gitignore for Node, Python, Rust, Go, Java, Swift, .NET, C/C++ or the web, a licence, the default branch — and optionally create it on a host right away.
- **Clone from your accounts:** pick one of your own repositories from a searchable list instead of pasting a URL.
- **View on the web and pull requests:** open the branch or a commit on its host, or start a pull/merge request, from the toolbar, tabs and history.
- **Several windows:** New Window (⌘N), Open in New Window, and tabs or worktrees in a window of their own. **Closing the last tab closes the window, and closing the last window quits Twig completely.**
- **Right-click in the Finder, File Explorer and Linux file managers:** Open in Twig, Show History in Twig, Blame in Twig (Settings → Right-click). A running Twig takes the request instead of starting again.
- **Dock menu (macOS):** New Window, Open, Open Recent, Clone, New, Commit, Fetch All, Pull, Push, Publish, AI, Command Palette, plus a More submenu.
- **Right-click everywhere:** the title bar, every toolbar button (pull with rebase, fast-forward only, push tags, force with lease, stash options…), tabs (close others, close to the right, copy path/URL/branch), the status bar, recent repositories and commits — with submenus, ✓ checks and keyboard navigation.
- **Small windows:** Twig now shrinks to 480 × 320 with nothing overlapping and nothing scrolling the window — toolbar buttons fold into ⋯, the sidebar and AI panel slide over the page, and the panes stack or narrow.
- **Worktrees:** several branches checked out at once, each in its own folder — add, open, lock, remove, prune.
- **Co-authors and signed commits** in the commit box; **Save as patch / Apply patch**, **Export as ZIP**, **Clean untracked files** (with a preview), **Optimize repository**, **Fetch every open repository**.
- **Colour everywhere, never pink:** five new hues (sky, indigo, coral, mint, sun); brackets coloured by depth, operators, types, constants, properties and escapes in diffs and AI answers; git commands coloured by part; conventional-commit types (feat, fix, docs…) in history; one colour per kind of file; every tab in its own colour.
- **Vector animations with sound:** commits, pushes, pulls, branches, merges, stashes, tags, conflicts, publishing, accounts, worktrees, cleaning and more each draw their own little picture; toast icons draw themselves; a growing tree on the start screen; Settings → Animations: lively, subtle or off. 20 new sounds.
- **FreeBSD build fixed** (the build machine ran out of memory), and a check-builds workflow that compiles and starts Twig on macOS, Windows, Linux and FreeBSD.
- **For the owner:** `npm run apple-sign` signs, notarizes and staples with an Apple Developer ID (or builds a Mac App Store package) once you join the Apple Developer Program; the GitHub repositories get their description, website and topics on every release.

## Twig 1.0.2 — 08 Oct 2026

- **Fixed:** with the AI panel open, the commit box (message, Write message / Describe / Explain, Amend, Sign-off) spilled out of its column into the diff — it now stays inside and wraps. On narrow windows the sidebar steps aside while the AI panel is open.
- **Fixed:** "Explain" in the commit box with nothing staged sent an empty question, so the AI asked what to explain — it now explains unstaged or new files, or says the tree is clean.
- **Six sound packs:** Soft, Crisp, Retro 8-bit, Glass, Wood and Space (Settings → Sound pack), plus new sounds for streaks, a clean tree, branch switches and tags.
- **Commit streaks:** your 1st, 3rd, 5th, 10th, 20th and 50th commit of the day get a toast, a fanfare and confetti.
- **A sapling grows** when the working tree is clean; files you stage or unstage glow as they land in their new list.
- **Branch switch sweep:** a gold line and a branch chip sweep under the title bar when the branch changes.
- **Living graph:** the current commit pulses in the history graph; AI answers glow when they finish; Pro activation rains confetti.

## Twig 1.0.1 — 08 Oct 2026

**Twig is now an AI Git client — and the AI is free for everyone.**

- **Twig AI, built in:** works the moment Twig opens — no account, no key, nothing to install (a fair daily allowance per computer).
- **GitHub Copilot and GitHub Models:** use the Copilot CLI with your Copilot subscription, or GitHub Models with your GitHub sign-in (`gh`) or a token.
- **Every local AI connects by itself:** Ollama, LM Studio, llama.cpp, llamafile, Jan, GPT4All, LocalAI, vLLM, KoboldCpp, text-generation-webui, Msty and AnythingLLM are found on this computer; Twig can start Ollama and download models into it with a progress bar.
- **Any AI on the internet:** OpenAI, Gemini, OpenRouter, Groq, Mistral, DeepSeek, Together, Fireworks, xAI, Cerebras, Perplexity — or any OpenAI-compatible URL with your key.
- **Write message / Describe:** the commit box writes the summary and description from your changes, streamed in as it thinks.
- **AI chat box** (⌘J) that knows your branch, changes and recent commits; every `git` command in an answer has a **Run** button, and risky ones ask twice.
- **Suggestion box:** instant offline suggestions (commit, pull, push, publish, resolve) plus AI suggestions for the next steps, each one click to run.
- **Explain everything:** a “?” beside Amend, Sign-off, Reset, Rebase and more, a searchable glossary of 33 Git words, “Explain this commit”, “Explain these changes”, “Help me resolve this conflict” and pull-request descriptions for any branch.
- **Startup show:** the twig draws itself, leaves unfurl, sparks fly and “An AI Git client” types out — with its own sound (Settings → Startup to turn it off).
- **More motion and sound:** drifting leaves on the welcome screen, click ripples, a circular theme switch, a glowing AI button, typing dots, and new sounds for AI, running commands and startup.

- **Windows on Arm**: a native ARM64 installer (`Twig_<version>_arm64-setup.exe`); the PowerShell installer picks it automatically, and it updates itself.
- **Linux ARM64**: a `.deb` for 64-bit ARM (Raspberry Pi OS 64-bit, ARM laptops and servers, ARM Chromebooks) that updates itself; the one-line installer picks it on ARM.
- **Linux .deb installs now update themselves** (x86_64 and ARM64), not only the AppImage.
- **ChromeOS**: install guide for the Linux development environment, on Intel/AMD and ARM Chromebooks; the one-line installer detects ChromeOS.
- **FreeBSD**: an amd64 tarball (`Twig_<version>_freebsd_amd64.tar.gz`) with an `install.sh` for `/usr/local`; the one-line installer works on FreeBSD too. FreeBSD builds do not update themselves — rerun the installer.
- Haiku isn't supported: Twig's window engine (Tauri/WebKit) has no Haiku port.

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
