# krunker-loader

Krunker.io cheat stack by **HVHM** — our own keyless build derived from the AimbaeShiro / Quirify lineage.

## What's in this repo

| File | What it is |
|------|------------|
| `hvhm.user.js` | **Our cheat (primary).** Standalone Tampermonkey/Violentmonkey userscript. Aimbot, ESP/wallhack, chams (player + weapon, self, RGB), FOV changer, skin changer, bhop, mod menu. Neutral/ImGui-style UI (hvhmail palette). |
| `game_3_0.js` | Clean Krunker client used by the loader. |
| `krunker_loader.user.js` | Optional keyless loader (Quirify keyauth emulation) that boots `game_3_0.js` into krunker.io. |

## Install (recommended — standalone cheat)

1. Install **Tampermonkey** or **Violentmonkey**.
2. Open the raw script and add it as a userscript:
   `https://raw.githubusercontent.com/levifrsn63/krunker-loader/main/hvhm.user.js`
3. Go to `https://krunker.io/` — the cheat auto-injects (sets the `__xVb92__` anti-tamper token at `document-start`) and the mod menu appears.

> Press the menu hotkey (default **P**) to open the HVHM mod menu.

## Optional: keyless loader

If you want the loader to boot the clean `game_3_0.js` client instead of the bundled one, install
`https://raw.githubusercontent.com/levifrsn63/krunker-loader/main/krunker_loader.user.js`
as well. It emulates the license/heartbeat checks locally, so no key is required.

## Features (hvhm.user.js)

- **Aimbot** — smooth aim, FOV-based target selection, trigger/recoil options.
- **ESP / Wallhack** — boxes, lines, names, health, distance (neutral colors).
- **Chams** — player highlight (enemy/team color, self, opacity, animated RGB) + **weapon chams** (viewmodel color/opacity). Through-walls option.
- **FOV changer** — live camera FOV slider.
- **Skin changer / bhop / mod menu** — full keybindable settings UI.

## Notes

- No license key required; the anti-tamper token is set locally.
- The in-game menu uses a monochrome hvhmail/ImGui look (black background, white borders/accents, monospace values).
