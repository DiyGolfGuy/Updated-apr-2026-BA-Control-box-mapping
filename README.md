# BA Custom Control Box Remapper

**Add secondary functions to your BA Custom Golf Simulator Control Box — no drivers, no installs, just one .exe.**

Built for the [BA Custom Products](https://www.bacustomproducts.com) GSPRO V2 Wireless Golf Simulator Control Box.

---

## What It Does

Your BA Custom control box works perfectly out of the box with its 14 default GSPro hotkeys. This remapper is an **optional advanced tool** that adds secondary functions to each button using a hold-to-activate FN key — like a shift key for your control box.

- **FN + Button = Secondary Action** — map any button to a different GSPro hotkey or a screen click
- **Tap FN Alone = Normal Function** — the FN button still sends its primary key when tapped
- **Toggle ON/OFF** — press Ctrl+F12 or click the button. Turn it off when you need to type.
- **Multiple Profiles** — set up different configs for 2-man scramble, solo practice, league play, etc.
- **Screen Click Mode** — FN + button moves the mouse to a saved position, clicks, then hides the cursor
- **No drivers or dependencies** — one .exe file, runs from anywhere

---

## Download

Go to [Releases](../../releases) and download **BARemapper.exe**. That's it — just run it.

---

## Quick Start

1. **Run BARemapper.exe** — a window opens immediately
2. **Click "Open Button Builder"** — green layout matching your box appears
3. **Click any button** to set its secondary FN function
4. **Pick your FN key** — default is Reset Aim (A), change it in the dropdown
5. **Save & Close** the builder
6. **Click "Turn ON"** (or press Ctrl+F12) to activate remapping
7. **Hold FN + press a button** on your control box to fire the secondary action

**Turn remapping OFF** (Ctrl+F12) when you need to type course names or use your keyboard normally.

---

## Features

### Primary Functions (Always Work)
| Button | Key | GSPro Function |
|--------|-----|----------------|
| Mulligan | Ctrl+M | Mulligan |
| Heat Map | Y | Heat Map |
| Putt | U | Putt Toggle |
| Flyover | O | Flyover |
| Club Up | I | Club Up |
| Club Down | K | Club Down |
| Reset Aim | A | Aim Reset |
| Tee Left | C | Tee Position Left |
| Tee Right | V | Tee Position Right |
| Shot Cam | J | Shot Camera |
| Arrows | Arrow Keys | Navigation |

### Secondary Functions (FN + Button)
Two types available per button:

**Key Mode** — FN + button sends a different GSPro hotkey. Example: FN + Tee Left sends B (Camera Clip).

**Click Mode** — FN + button clicks a specific screen location. The mouse moves to the saved position, waits 500ms, clicks, then moves to the top-left corner to get out of the way.

### Profiles
Create named profiles for different game formats. Switch instantly from the main window dropdown.

### Other
- Start with Windows checkbox
- Remembers window position
- Minimizes to system tray (click X to minimize, right-click tray to reopen)
- Help guide built in
- Phantom key suppression (Windows key, Pause key from box)

---

## How FN Works

The FN button has dual behavior:

- **Tap alone** — sends its normal primary function (e.g., A = Aim Reset)
- **Hold + press another button** — fires the secondary function for that button

This means you never lose a button. The FN key still does its job when tapped.

---

## Building From Source

### Requirements
- [AutoHotkey v1.1](https://www.autohotkey.com/) (not v2)

### Run
Double-click `BARemapper.ahk`

### Compile to .exe
1. Open `Ahk2Exe.exe` (included with AutoHotkey at `C:\Program Files\AutoHotkey\Compiler\`)
2. Source: `BARemapper.ahk`
3. Destination: `BARemapper.exe`
4. Custom Icon: `BARemapper.ico` (optional)
5. Click Convert

The compiled .exe runs standalone — customers don't need AutoHotkey installed.

---

## GSPro Hotkey Reference

All available GSPro hotkeys that can be assigned as secondary functions:

| Key | Function | Key | Function |
|-----|----------|-----|----------|
| A | Aim Reset | O | Flyover |
| B | Camera Clip | P | Pin Indicator |
| C | Tee Left | Q | Minimap Zoom Out |
| D | Vertical Dots | R | Rangefinder |
| F | FPS Toggle | S | Map Expand |
| G | Green Grid | T | Scorecard |
| H | Hide UI | U | Putt Toggle |
| I | Club Up | V | Tee Right |
| J | Shot Cam | W | Minimap Zoom In |
| K | Club Down | Y | Heat Map |
| L | Lighting | Z | 3D Grass Toggle |
| N | Switch Hand | Ctrl+M | Mulligan |
| F1 | Clear Tracer | Space | Fast Forward |
| F3 | Aimpoint | Tab | Shortcuts |
| F5 | Free Look | | |

---

## Important Notes

- **Turn OFF when typing** — when remapping is ON, box keys are intercepted from all keyboards. Press Ctrl+F12 to toggle off before typing course names or chatting.
- **Config file** — settings save to `ba_remapper.ini` in the same folder as the .exe. Delete this file to start fresh.
- **Profiles** — stored in the same .ini file. Each profile has its own FN button and secondary mappings.

---

## Support

**BA Custom Products**
- Web: [bacustomproducts.com](https://www.bacustomproducts.com)
- Email: bacustomproducts@gmail.com
- Phone: (218) 684-3290 (call or text)

---

## License

This software is provided by BA Custom Products for use with their golf simulator control boxes. 
