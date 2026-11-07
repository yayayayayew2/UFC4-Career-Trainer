<div align="center">

# UFC 4 Career Mode Trainer

**A Cheat Engine table for UFC 4 Career Mode, controlled entirely from your NUMPAD.**

![Game](https://img.shields.io/badge/Game-UFC%204-red)
![Tested on](https://img.shields.io/badge/Tested%20on-CUSA14204-blue)
![Tool](https://img.shields.io/badge/Tool-Cheat%20Engine-orange)
![Mode](https://img.shields.io/badge/Mode-Offline%20only-green)

</div>

> [!WARNING]
> **Offline use only.** Do not use this online.
> This table was made and tested **only on UFC 4 CUSA14204**. Other versions or regions may use different memory addresses, and features may not work or may fail to install. Use at your own risk and **back up your save before you start.**

---

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Stamina Guide](#stamina-guide)
- [Hotkey Reference](#hotkey-reference)
- [On-Screen Notifications](#on-screen-notifications)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

---

## Features

| Feature | What it does | Hotkey |
|---|---|---|
| **Evolution Points** | When your Evo Points drop below 100, they are automatically set to **5000**. | `NUMPAD 9` |
| **Fitness** | Locks Fitness at **PEAK**. | `NUMPAD /` |
| **Move EXP** | Turn it on, then spar or fight. Moves you use are detected automatically and their EXP is boosted. Keep using a move until it reaches **level 5**. | `NUMPAD -` |
| **Money** | When your money is below 30,000, it is automatically set to **5,000,000**. | `NUMPAD 0` |
| **Stamina** | Locks **your fighter's** yellow and/or white stamina. See the [Stamina Guide](#stamina-guide). | `NUMPAD *`, `8`, `7` |
| **All Career features** | Turns every career feature on or off at once (includes Weekly Point). | `NUMPAD +` |
| **Weekly Point** | Locks Weekly Point at 100. **No hotkey**, enable it manually in the table. | Manual |

> [!CAUTION]
> **Weekly Point is not recommended.** It can break your Career Mode and you may have to start over. `NUMPAD +` also turns it on, so enable features one by one if you want to avoid it.

Every hotkey is a **toggle**: press once to turn the feature on, press again to turn it off.

---

## Requirements

- UFC 4 **CUSA14204**
- [Cheat Engine](https://www.cheatengine.org/)
- A keyboard with a **NUMPAD** (**NumLock must be ON**)

---

## Quick Start

1. Start the game and enter **Career Mode**.
2. Open Cheat Engine and attach it to the UFC 4 process.
3. Open `UFC4_Gabungan.CT` in Cheat Engine.
4. Press the hotkeys from the [Hotkey Reference](#hotkey-reference), or tick the entries manually in the table.
5. Watch the [on-screen notification](#on-screen-notifications) to confirm each feature turned on.

> Press each key **once** and wait a moment. Don't spam the keys.

---

## Stamina Guide

Stamina locks **your fighter's** yellow and white stamina only, not the opponent's. Each one can be enabled separately.

### First time (once per game session)

1. Enter a **fight**.
2. Press `NUMPAD *` to install the stamina hook. Wait for the **"Stamina hook INSTALLED"** notification. Cheat Engine may freeze for a few seconds while it scans memory. That's normal.
3. Turn on the stamina you want, one or both. **You only need to enable them once.** They stay on in later fights.

| Key | Stamina |
|---|---|
| `NUMPAD 8` | **Yellow** stamina (unlimited, never tired) |
| `NUMPAD 7` | **White** stamina (held at max) |

### Every new fight (required)

1. Press `NUMPAD 4` to **reset**.
2. Play for a few seconds so the game detects both fighters.
3. Select your side:

| Key | Your position |
|---|---|
| `NUMPAD 5` | You are on the **LEFT** |
| `NUMPAD 6` | You are on the **RIGHT** |

When you see **"Player ... side SELECTED"**, stamina is working for your fighter.

> [!IMPORTANT]
> If you skip the reset and side selection in a new fight, stamina may not work correctly. Just repeat the steps above.

<details>
<summary><b>Manual fighter pick (backup)</b></summary>

Use this only if side selection (`5` / `6`) fails.

1. Press `NUMPAD 1` to test an object. Its stamina drops to 20.
2. If **your** bar drops, press `NUMPAD 2` to select it.
3. If it's not your bar, press `NUMPAD 1` again to test the next object.

</details>

---

## Hotkey Reference

| Key | Action |
|---|---|
| `NUMPAD 9` | Evolution Points on/off |
| `NUMPAD 0` | Money on/off |
| `NUMPAD /` | Fitness (Peak) on/off |
| `NUMPAD -` | Move EXP on/off |
| `NUMPAD +` | All career features on/off (includes Weekly Point) |
| `NUMPAD *` | Install / remove the Stamina hook |
| `NUMPAD 8` | Yellow stamina on/off |
| `NUMPAD 7` | White stamina on/off |
| `NUMPAD 4` | Reset (every new fight) |
| `NUMPAD 5` | Select LEFT side |
| `NUMPAD 6` | Select RIGHT side |
| `NUMPAD 3` | Turn off yellow and white stamina |
| `NUMPAD 1` / `2` | Manual fighter pick (backup) |

---

## On-Screen Notifications

A small notification box appears in the top-left corner of the screen every time you press a key, so you can tell it worked even in fullscreen.

| Badge | Meaning |
|---|---|
| **ACTIVE** (green) | Feature turned on |
| **OFF** (orange) | Feature turned off |
| **LOADING** (blue) | Installing, please wait |
| **ERROR** (red) | Something failed, see [Troubleshooting](#troubleshooting) |

If you can't see the notifications, switch the game to **borderless or windowed** mode.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| `FAILED to install` | You are not in Career Mode or a fight yet. Enter one, then press the key again. |
| No notification appears | Switch the game to borderless or windowed mode. |
| Stamina not working in a new fight | Press `NUMPAD 4`, play a few seconds, then press `NUMPAD 5` or `6` again. |
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
