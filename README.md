# krunker-loader

A Krunker.io userscript loader that injects the latest \game_3_0.js\ client (fetched live from Quirify's game-data repo) and runs the Quirify cheat stack **without a license key** (keyauth is emulated locally).

## Features
- Boots the current \game_3_0.js\ client into krunker.io (sets the \__xVb92__\ anti-tamper token).
- Loads the full Quirify cheat stack (aimbot, ESP/wallhack, skin changer, hotkey menu).
- License / heartbeat checks to \krunker.twitchfollows.de\ are answered locally with a valid response, so no key is required.
- Debug panel: press \ (backtick) or F8 to show/hide.

## Install
1. Install Tampermonkey / Violentmonkey.
2. Add \krunker_loader.user.js\ as a userscript.
3. Open https://krunker.io/ — the game loads from \game_3_0.js\ and the cheat runs keyless.

> The game client is pulled live from Quirify's GitHub repo, so it stays current automatically.
