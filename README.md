# PhotoTriage

Version 1.0 of **PhotoTriage**, a little Mac app I built because I got tired of deleting files manually one at a time. Right-click, move to trash, confirm, repeat — multiply that by ten thousand photos and you never actually clean anything up.
<div align="center">

<img src="Image 1.jpeg" width="128" alt="PhotoTriage icon" />

# PhotoTriage

**Keyboard-first photo cleanup for macOS.**

![License](https://img.shields.io/github/license/FatBoy721/PhotoTriage?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-14%2B-black?style=flat-square&logo=apple&logoColor=white)
![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-ready-success?style=flat-square&logo=apple)


[Download latest release](https://github.com/FatBoy721/PhotoTriage/releases/latest) · [Report a bug](https://github.com/FatBoy721/PhotoTriage/issues)

</div>

---

## Why

Got tired of deleting photos one by one. Made something that turns it into a keyboard game. Arrow keys do everything, nothing actually deletes until you confirm at the end.

## Features

- Keyboard-first triage — arrow keys only
- Finder folder support
- Apple Photos library support
- Review queue before final delete
- Dark glass macOS UI
- Menu bar + full window
- Zero telemetry, zero network

## Install

1. Download the latest DMG from [Releases](https://github.com/FatBoy721/PhotoTriage/releases/latest).
2. Drag the app into Applications.
3. First launch: right-click → **Open** → **Open** (ad-hoc signed, so Gatekeeper warns once).

## Keyboard map

| Key | Action |
|-----|--------|
| ← | Keep |
| → | Mark for delete |
| ↑ | Favorite |
| ↓ | Skip |
| Z | Undo |
| ⌘↩ | Finish & review |

## Requirements

macOS 14+. Apple Silicon or Intel.

## License

MIT — see [LICENSE](LICENSE).
So I made this. Four arrow keys, a review queue, one final confirmation. Somewhere between a game and a productivity tool — fast enough to not feel like chores, safe enough that you can't accidentally nuke your library.

### The whole workflow
- ← keep · → mark for delete · ↑ favorite · ↓ skip · Z to undo

Nothing is actually deleted until you hit confirm on the review screen at the end.

### What's in this build
- Finder folder support
- Apple Photos library support (via PhotoKit)
- Post-session review queue with a final confirm step
- Dark, glassy desktop UI
- Menu bar access + full app window
- Zero telemetry, zero network calls

### Install
1. Download **PhotoTriage-1.0.dmg** below.
2. Open the DMG and drag the app into **Applications**.
3. First launch: right-click → **Open** → **Open** (ad-hoc signed for now, so Gatekeeper will warn you once).

### Requirements
macOS 14+. Apple Silicon or Intel.
