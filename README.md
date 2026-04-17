# PhotoTriage

Version 1.0 of **PhotoTriage**, a little Mac app I built because I got tired of deleting files manually one at a time. Right-click, move to trash, confirm, repeat — multiply that by ten thousand photos and you never actually clean anything up.

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
