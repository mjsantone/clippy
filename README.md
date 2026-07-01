# 📎 CLIPPY.EXE — The Office Assistant Strikes Back

An epic 90s-Windows side-scroller starring the one and only Clippy, rendered
with hand-placed pixel art and running inside a fully chromed Windows 95
window — teal desktop, Start button, tray clock and all.

![Title screen](docs/title.png)

## Play it

Zero dependencies, zero build step. Just open the file:

```
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

Or serve it if you prefer: `npx serve .`

## The game

It is 1997. Clippy hops endlessly across a desktop metropolis of window-pane
skyscrapers, along a ground made of infinite taskbar. The OS itself is out to
get him.

![Gameplay](docs/gameplay.png)

- **Jump** over `Error` dialogs, recycle bins, and Blue-Screen monoliths
- **Double-jump** (with a full 360° paperclip spin) to clear stacked crash dialogs
- **Duck** under garish blinking banner ads (*FREE RAM!!! >> CLICK HERE <<*)
- **Dodge** winged hourglass cursors — time flies
- **Collect** 3.5" floppy disks (25 pts each, 1.44 MB of pure skill)
- **Grab the rainbow CD-ROM** to enter *UNREGISTERED HYPERCLIP MODE* and smash
  windows into flying UI shards
- **Survive** through nine zones: The Teal Desktop → Spreadsheet Canyon →
  Mail Merge Marshes → Dial-Up Dunes → Comic Sans Grove → The Blue Screen
  Badlands → Recycle Bin Abyss → System32 Catacombs → The Registry (Do Not Edit)

Clippy provides unsolicited commentary throughout, naturally.
*"It looks like you're trying to survive. Would you like help with that?"*

When you die — and you will — you get the full Blue Screen of Death, with your
score formatted as a fatal exception report.

![BSOD game over](docs/bsod.png)

## Controls

| Key | Action |
| --- | --- |
| `Space` / `↑` / `W` | Jump (press twice to double-jump) |
| `↓` / `S` | Duck (in mid-air: fast-fall) |
| `Enter` | Start / reboot after a crash |
| `P` | Pause |
| `M` | Mute |
| Click / tap | Jump (tap the bottom of the screen to duck) |

## 90s features, lovingly recreated

- Fake BIOS boot sequence (`Memory Test: 640K ... OK`) with a chunky loading bar
- Chiptune soundtrack and bleepy sound effects via WebAudio — no audio files
- CRT scanline overlay
- The sun is a beveled gray button, because everything is a widget in 1997
- Scrolling taskbar ground with embedded task buttons (`DOOM.EXE`, `winmine.exe`,
  `A:\ not ready`)
- Working menu bar (`File > New Game`), About dialog, and a Start button that is
  busy defragmenting (estimated time remaining: 14 years)
- High scores persist to `A:\HISCORE.INI` (fine, `localStorage`)

## Credits

Clippy pixel-art body, eye-animation sequences, and signature hop pattern ported
from the original `Clippy.tsx` canvas component. He has been waiting since 1997.
All he ever wanted was to help.
