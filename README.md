# DarkTriad

![DarkTriad logo](media/darktriad-logo.png)

DarkTriad is a private-use Minecraft Fabric client mod for 1.21.10.

## Requirements
- Minecraft 1.21.10
- Java 21
- Fabric Loader 0.18.4+
- Fabric API 0.138.4+1.21.10

## Install (Client)
1) Install Fabric Loader for 1.21.10.
2) Download Fabric API `0.138.4+1.21.10` from: https://modrinth.com/mod/fabric-api/version/0.138.4+1.21.10
3) Download `darktriad-1.0.0.jar` from: https://github.com/OmgDezzz/DarkTriad/raw/main/darktriad-1.0.0.jar
4) Place both jars into your `.minecraft/mods` folder.
5) Launch Minecraft using the Fabric profile.

## Default Keybinds
- Open menu: `=`
- X-ray: `X`
- KillAura: `C`
- BowAimbot: `V`
- AutoFarm: `U`
- AutoTree: `I`

Keybinds are configurable in the in-game menu.

## Features (Client-Side)
### Combat
- **KillAura**: Auto-attacks nearby entities with smart target filters and adjustable range, timed to Minecraft’s attack cooldown for smooth, human‑like swings.
- **BowAimbot (experimental)**: Smooth, configurable bow aim assist with prediction and smoothing sliders; locks during draw to keep shots steady and consistent.
- **AutoTotem**: Instantly swaps a totem into your offhand at low health to save you from lethal hits.
- **AutoShield**: While you’re holding a weapon, it auto‑swaps to a shield on right‑click and instantly switches back to your weapon when you release.

### Vision / Rendering
- **X-ray (Sodium compatible)**: Hides non‑ore blocks and highlights ores/containers with a clean, shader‑friendly render path; works in both Vanilla and Sodium.
- **Fullbright**: Night‑vision based brightness that stays stable with shaders/Sodium for clear visibility at all times.
- **ESP**: High‑contrast player, mob, and item overlays that render through blocks so you can see targets and loot through walls, underground, and across terrain.
- **HealthTags**: Wurst‑style health numbers over entities for instant combat awareness.
- **NoFireOverlay**: Removes the fire overlay so your screen stays clear in combat.
- **NoWeather**: Disables rain visuals to keep visibility crisp.
- **ShieldLower**: Lowers the shield overlay so you keep a wider field of view.

### Movement / World
- **QuickBreak**: Client‑side block breaking speed multiplier for faster mining and cleanup.
- **NoFall**: Basic no‑fall toggle to reduce accidental fall damage during movement.
- **MaceDMG**: Damage boost toggle for the mace when you want heavier hits.

### Bots / Automation
- **AutoFarm**: Smart harvest + replant with modes for **collect‑only** or **plant‑only**. Includes a batch mode to act on multiple blocks at once, or single‑block mode for more legit‑looking behavior.
- **AutoTree (experimental)**: A full tree bot that searches, paths, and harvests with movement that includes jumping, FOV awareness, and dynamic target selection. It also evaluates when to give up on a tree and move to the next to avoid getting stuck.
- **AutoTool**: Automatically swaps to the best tool for the block you’re mining, then restores your previous item.

### UI / UX
- **Modern GUI**: Crisp toggles and dedicated config screens for each feature.
- **Config persistence**: `config/darktriad.json` keeps your settings exactly how you left them.
- **Status HUD**: Shows enabled features with category filters for clean visibility.

## Notes
- This mod is intended for private servers with consent.
- Config file: `config/darktriad.json`
- This project was made with the collaboration of AI, including OpenAI's Codex and Anthropic's Claude Code.

## Project Status
This project is currently abandoned as my time is committed to other projects. If there is public interest, I may develop it further.
This GitHub repository is only for downloading the cheat client and does not include the full project folder.
If you want to build on this project, reach out to me on Instagram at `VICTOR_NDEZ` and I can share the full project folder so you can continue development.

## Media
### Menu UI
![Main menu UI](media/2026-01-22_10.35.19.png)

### ESP
![ESP on mobs and items](media/2026-01-22_10.36.30.png)

### X-ray
![X-ray enabled](media/2026-01-22_10.36.48.png)

### X-ray Block Selection
![X-ray block selection menu](media/2026-01-22_10.37.27.png)

### AutoFarm Settings
![AutoFarm settings menu](media/2026-01-22_10.37.44.png)

### BowAimbot Settings
![BowAimbot settings](media/2026-01-22_10.41.03.png)

### Item ESP Settings
![Item ESP settings with color picker and item selection](media/2026-01-22_10.41.32.png)

### Keybinds
![Keybinds menu](media/2026-01-22_10.43.50.png)

## License
All rights reserved. See `LICENSE`.
