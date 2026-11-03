# Hephaestus × Better Combat Compatibility

Resource-only compatibility mod providing Better Combat (by Daedalus) weapon attributes for the assembled tools in Hephaestus Tools.

## Release 1.0.0

- Minecraft: Java Edition **26.1.2**
- NeoForge: **26.1.2** (project is configured for `26.1.2.120`)
- Better Combat by Daedelus: tested with **3.2.2+26.1.2**, NeoForge
- Hephaestus Tools: **26.1.2**, NeoForge (tested with the author's in-game setup)

Install the jar on both client and server with those mods. Hephaestus Tools itself requires Hephaestus Forge. This mod contains no third-party code/assets; its data files point at Better Combat's built-in weapon presets.

## Included mappings

| Hephaestus Tools item | Better Combat preset |
|---|---|
| `hephaestus_tools:pickaxe` | `bettercombat:pickaxe` |
| `hephaestus_tools:sledge_hammer` | `bettercombat:hammer` |
| `hephaestus_tools:vein_hammer` | `bettercombat:hammer` |
| `hephaestus_tools:mattock` | `bettercombat:axe` |
| `hephaestus_tools:paxel` | `bettercombat:pickaxe` |
| `hephaestus_tools:excavator` | `bettercombat:hammer` |
| `hephaestus_tools:hand_axe` | `bettercombat:axe` |
| `hephaestus_tools:broad_axe` | `bettercombat:heavy_axe` |
| `hephaestus_tools:kama` | `bettercombat:sickle` |
| `hephaestus_tools:scythe` | `bettercombat:scythe` |
| `hephaestus_tools:dagger` | `bettercombat:dagger` |
| `hephaestus_tools:sword` | `bettercombat:sword` |
| `hephaestus_tools:cleaver` | `bettercombat:claymore` |

## Build from source

Requirements: Java 25 and Gradle 9.1+. Run `gradle build`; output is in `build/libs/`. The project disables Minecraft source recompilation because the mod is resource-only, reducing build setup and memory usage.

## License and attribution

The compatibility project's original files are licensed under MIT (see `LICENSE`). Hephaestus Tools and Better Combat are separate projects; use their respective licenses and download their mods from their official project pages.

- Better Combat by Daedalus: https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus
- Hephaestus Tools: https://www.curseforge.com/minecraft/mc-mods/hephaestus-tools
- Hephaestus Forge: https://www.curseforge.com/minecraft/mc-mods/hephaestus-forge
