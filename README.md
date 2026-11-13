<div align="center">

# UFC 4 Career Mode Trainer v2.0

**A Cheat Engine table for UFC 4 Career Mode, controlled entirely from your NUMPAD, with an on-screen overlay.**

![Game](https://img.shields.io/badge/Game-UFC%204-red)
![Tested on](https://img.shields.io/badge/Tested%20on-CUSA14204%20%7C%20CUSA14209-blue)
![Tool](https://img.shields.io/badge/Tool-Cheat%20Engine-orange)
![Mode](https://img.shields.io/badge/Mode-Offline%20only-green)
![Version](https://img.shields.io/badge/Version-2.0-purple)

</div>

> [!WARNING]
> **Offline use only.** Do not use this online.
> This table was made and tested on **UFC 4 CUSA14204 and CUSA14209**. No bugs found so far on either version. Other versions or regions may use different memory addresses, and features may not work or may fail to install. Use at your own risk and **back up your save before you start.**

---

## Table of Contents

- [What's New in v2.0](#whats-new-in-v20)
- [Features](#features)
- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Stamina Guide](#stamina-guide)
- [Hotkey Reference](#hotkey-reference)
- [On-Screen Overlay](#on-screen-overlay)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

---

## What's New in v2.0

- **New overlay.** A feature box with every hotkey and an ON/OFF badge, plus a status bar that lists the features that are currently active.
- **Simpler stamina.** Pick a side with `NUMPAD 1` / `2` / `3` and the stamina hook installs itself. **Yellow and white stamina turn on together automatically.** There are no separate yellow/white keys anymore.
- **New "Both" mode.** `NUMPAD 3` locks the stamina of both fighters at once.
- **No more reset step.** The old per-fight reset (`NUMPAD 4`) is gone. The fighter is detected and re-locked automatically.
- **Move Unlocker.** Unlocks all locked and empty move slots (Lv 0 to Lv 1).
- **New hotkey layout.** Stamina uses `NUMPAD 1`, `2`, `3` and `0`. Career features moved to `NUMPAD 4` to `8`.
- **`NUMPAD +` is now safe.** It no longer turns on Weekly Point.
- **Weekly Point has no hotkey.** Manual only, because it is not recommended.

---

## Features

| Feature | What it does | Hotkey |
|---|---|---|
| **Stamina** | Locks yellow and white stamina for your fighter (left or right) or for both fighters. See the [Stamina Guide](#stamina-guide). | `NUMPAD 1` `2` `3` `0` |
| **Money** | When your money is below 30,000, it is automatically set to **5,000,000**. | `NUMPAD 4` |
| **Evolution Points** | When your Evo Points drop below 100, they are automatically set to **5000**. | `NUMPAD 5` |
| **Fitness** | Locks Fitness at **PEAK**. | `NUMPAD 6` |
| **Move Unlocker** | Unlocks all locked and empty move slots (Lv 0 to Lv 1). Turn it on, then open or re-enter the Moves menu. | `NUMPAD 7` |
| **Move EXP** | Turn it on, then spar or fight. Moves you use are detected automatically and their EXP is boosted. Keep using a move until it reaches **level 5**. | `NUMPAD 8` |
| **All Career features** | Turns Money, Evo Points, Fitness, Move Unlocker and Move EXP on or off at once. **Does not include Weekly Point.** | `NUMPAD +` |
| **Weekly Point** | Locks Weekly Point at 100. **No hotkey**, enable it manually in the table. | Manual |

> [!CAUTION]
> **Weekly Point is not recommended.** It can break your Career Mode and you may have to start over. That is why it has no hotkey and is not part of `NUMPAD +`.

Every hotkey is a **toggle**: press once to turn the feature on, press again to turn it off.

---

## Requirements

- UFC 4 **CUSA14204** or **CUSA14209**
- [Cheat Engine](https://www.cheatengine.org/)
- A keyboard with a **NUMPAD** (**NumLock must be ON**)

---

## Quick Start

1. Start the game and enter **Career Mode**.
2. Open Cheat Engine and attach it to the UFC 4 process.
3. Open `UFC4_CareerMode_Trainer.CT` in Cheat Engine.
4. Press the hotkeys from the [Hotkey Reference](#hotkey-reference), or tick the entries manually in the table.
5. Watch the [on-screen overlay](#on-screen-overlay) to confirm each feature turned on.

> Press each key **once** and wait a moment. Don't spam the keys.

---

## Stamina Guide

Stamina locks **yellow and white stamina together**. You choose whose stamina to lock:

| Key | Result |
|---|---|
| `NUMPAD 1` | Lock the **LEFT** fighter |
| `NUMPAD 2` | Lock the **RIGHT** fighter |
| `NUMPAD 3` | Lock **BOTH** fighters |
| `NUMPAD 0` | Turn stamina **OFF** |

### How to use

1. Enter a **fight**.
2. Press `NUMPAD 1`, `2` or `3`.

That is all. The first time you do this in a game session, the stamina hook installs itself. Cheat Engine may freeze for a few seconds while it scans memory, and that is normal. Wait for the overlay to show **"Stamina ... SELECTED"**.

Pressing the same key again turns stamina off, just like the other toggles. `NUMPAD 0` always turns it off.

### Notes

- Stamina must be turned on from **inside a fight**, because the hook can only install there.
- The hook stays installed after `NUMPAD 0`. Only stamina turns off. To remove the hook completely, untick **Stamina Master Hook** in the table, or press `NUMPAD *`.
- `NUMPAD *` is optional. It installs or removes the hook by hand, but you normally never need it.
- If stamina stops working in a new fight, press `NUMPAD 0`, then press your side again.

---

## Hotkey Reference

| Key | Action |
|---|---|
| `NUMPAD 1` | Stamina: LEFT fighter |
| `NUMPAD 2` | Stamina: RIGHT fighter |
| `NUMPAD 3` | Stamina: BOTH fighters |
| `NUMPAD 0` | Stamina: OFF |
| `NUMPAD 4` | Money on/off |
| `NUMPAD 5` | Evolution Points on/off |
| `NUMPAD 6` | Fitness (Peak) on/off |
| `NUMPAD 7` | Move Unlocker on/off |
| `NUMPAD 8` | Move EXP on/off |
| `NUMPAD +` | All career features on/off (**without** Weekly Point) |
| `NUMPAD *` | Install / remove the Stamina hook (optional) |
| *(none)* | Weekly Point, manual only |

---

## On-Screen Overlay

An overlay appears in the top-left corner of the screen every time you press a key, so you can tell it worked even in fullscreen.

- **Feature box.** Lists every feature with its hotkey and a badge: **ON** (green) or **OFF** (grey). Stamina shows **LEFT**, **RIGHT** or **BOTH** when active. The box hides itself after a few seconds.
- **Status bar.** A bar under the box lists the features that are currently active. It stays on screen as long as at least one feature is on.
- **Message line.** The last line of the box shows the latest message.

| Message color | Meaning |
|---|---|
| Green | Feature turned on |
| Orange | Feature turned off |
| Blue | Installing, please wait |
| Red | Something failed, see [Troubleshooting](#troubleshooting) |

If you can't see the overlay, switch the game to **borderless or windowed** mode.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| `FAILED to install` | You are not in Career Mode or a fight yet. Enter one, then press the key again. |
| Stamina does nothing | Make sure you are **inside a fight**, then press `NUMPAD 1`, `2` or `3` again. |
| Stamina stopped in a new fight | Press `NUMPAD 0`, then press your side again. |
| Move Unlocker shows nothing | Open or re-enter the Moves menu after turning it on. |
| No overlay appears | Switch the game to borderless or windowed mode. |
| Keys do nothing | Check that **NumLock is ON** and the table is loaded in Cheat Engine. |
| Hooks seem stuck | Restart the game, reattach Cheat Engine, and reload the table. |

---

## Credits

- **GoldHEN**: original stamina method, converted to Cheat Engine for this table
- **Portheon**

---

<div align="center">

**Offline use only. Back up your save. Use at your own risk.**

</div>
