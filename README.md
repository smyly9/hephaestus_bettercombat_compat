# Hephaestus × Better Combat compatibility (NeoForge 26.1.2)

Targets **Better Combat by Daedelus**.

## Included support

This is a resource-only NeoForge compatibility mod. It bundles Better Combat weapon-attribute JSON for all 13 assembled Hephaestus Tools weapons, using their IDs confirmed from the Hephaestus Tools 26.1 source. The files are under `data/hephaestus_tools/weapon_attributes/`.

| Item ID | Preset |
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

The presets are reasonable starting points based on item form, not upstream-authored balancing.

## Install

Install `hephaestus_bettercombat_compat-1.0.0.jar` in the `mods` folder **on both client and server**, alongside NeoForge 26.1.2, Better Combat, Hephaestus Forge, and Hephaestus Tools. Launch and test the 13 tools.

## References

- Better Combat: https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus/
- Better Combat JSON integration guide/source: https://github.com/ZsoltMolnarrr/BetterCombat
- Hephaestus Tools source and item registrations: https://github.com/JDKDigital/hephaestustools/tree/26.1/main
- Hephaestus Forge: https://www.curseforge.com/minecraft/mc-mods/hephaestus-forge
