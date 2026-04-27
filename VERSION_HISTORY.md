<!-- VERSION_HISTORY_AUTO_START -->
# VERSION_HISTORY

Updated: 2026-04-21
Repository: `openclaw-android`
Path: `/home/igorkan/repos/openclaw-android`

## Why This File Exists
- Captures major historical shifts in product direction, architecture, and look/structure.
- Makes older valid implementations easy to locate, compare, and branch from.

## Current Snapshot
- Commit count: 60
- Latest commit: `2c10f94` (2026-04-15) chore: update repository content and documentation
- First commit: `209511f` (2026-02-11) Initial release: OpenClaw Lite Android installer
- Primary branch: `main`
- Known tags: 0
- Tracked branches listed: 5

## Major Version Milestones
| Date | Commit | Change | Why it matters |
|---|---|---|---|
| 2026-02-11 | `209511f` | Initial release: OpenClaw Lite Android installer | Deployment/release milestone |
| 2026-02-12 | `8fa3cfd` | Merge remote-tracking branch 'origin/main' | Notable implementation milestone |
| 2026-02-18 | `c46059b` | Fix env var propagation, standalone safety, and script cleanup | Notable implementation milestone |
| 2026-02-18 | `a4d7b5e` | Add error handling for mktemp failures in update.sh | Notable implementation milestone |
| 2026-02-18 | `ff3097b` | Document PyYAML dependency in package table | Notable implementation milestone |
| 2026-02-18 | `830cfe2` | Open myopenclawhub.com link in new tab (target="_blank") | Notable implementation milestone |
| 2026-02-19 | `27d40b9` | Update troubleshooting documentation and improve install script output for Termux users | Presentation/look-and-feel change |
| 2026-04-15 | `2c10f94` | chore: update repository content and documentation | Notable implementation milestone |

## How To Recover Older Versions
1. View full history: `git log --graph --decorate --oneline --all`
2. Checkout a milestone commit (detached HEAD): `git checkout <commit-hash>`
3. Create a branch from an older version: `git switch -c retro/<label> <commit-hash>`
4. Return to current baseline: `git switch main`

## How To Compare Two Approaches (Look/Structure)
- Changed files overview: `git diff --name-status <old>..<new>`
- Structural footprint: `git diff --stat <old>..<new>`
- UI/layout deltas (if web app): `git diff <old>..<new> -- src app components styles public`
- Commit narrative between two versions: `git log --oneline <old>..<new>`

## Branches (Sample)
- `main`
- `origin`
- `origin/main`
- `upstream`
- `upstream/main`

## Project Title Signal
- OpenClaw on Android

<!-- VERSION_HISTORY_AUTO_END -->
