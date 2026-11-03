![Hephaestus x Better Combat Compat](/icon.png)
# Hephaestus x Better Combat Compatibility

A resource-only NeoForge mod adding Better Combat weapon attributes for Hephaestus Tools. 

## Compatibility

- Minecraft Java Edition 26.1.2
- NeoForge 26.1.2.120
- Better Combat by Daedelus
- Hephaestus Tools for Minecraft 26.1.2 (requires Hephaestus Forge)

Install the jar on both client and server alongside the dependencies.

## Build

Requirements: Java 25. From the project root, run:

```sh
./gradlew build
```

On Windows, run `gradlew.bat build`. Gradle 9.1.0 is provided by the wrapper. Since this mod contains only resources, its build skips Minecraft source decompilation/recompilation to reduce memory use. The jar is generated at `build/libs/`.

## Weapon mappings

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

## License and attribution

The compatibility project's original files are licensed under MIT (see `LICENSE`). Hephaestus Tools and Better Combat are separate projects; use their respective licenses and download those mods from their official pages.

- Better Combat: https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus
- Hephaestus Tools: https://www.curseforge.com/minecraft/mc-mods/hephaestus-tools
- Hephaestus Forge: https://www.curseforge.com/minecraft/mc-mods/hephaestus-forge
