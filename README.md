# GTNH Additional Mods
### [GTNH Wiki Page](https://wiki.gtnewhorizons.com/wiki/Additional_Mods)


## Required
[Shared Prospecting](https://github.com/Lyfts/SharedProspecting/releases/tag/2.0.4)

[Gregtorio Overlays](https://github.com/ah-OOG-ah/GregtorioOverlays/releases/tag/1.1.2)


## Recommended
[Just Enough Calculation](https://github.com/GTNewHorizons/JustEnoughCalculation/releases/tag/1.7.10-4.9)

[FPS Reducer](https://www.curseforge.com/minecraft/mc-mods/fps-reducer/files/all?page=1&pageSize=20&version=1.7.10)

[Extreme Sound Muffler: Legacy](https://github.com/Lyfts/ExtremeSoundMuffler-Legacy/releases/tag/1.0.12)

[WorldEdit CUI](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-forge-edition/files/all?page=1&pageSize=20&version=1.7.10)

[WorldEdit](https://github.com/GTNewHorizons/worldedit-gtnh/releases/tag/v0.0.8) (Normally server-side, only useful if you want singleplayer worldedit)

[MyCTMLib](https://github.com/ABKQPO/MyCTMLib/releases/tag/v1.2.5_28x) (Has no effect without Modernity)

## Recommended to disable/delete
[DefaultServerList](https://github.com/glowredman/DefaultServerList) 


## Server-side mods
[Shared Prospecting](https://github.com/Lyfts/SharedProspecting/releases/tag/2.0.4)

[Gregtorio Overlays](https://github.com/ah-OOG-ah/GregtorioOverlays/releases/tag/1.1.2)

[WorldEdit](https://github.com/GTNewHorizons/worldedit-gtnh/releases/tag/v0.0.8)

### Docker Compose
```yaml
services:
  server:
    ...
    environment:
      MODS: |
        https://github.com/Lyfts/SharedProspecting/releases/download/2.0.4/sharedprospecting-2.0.4.jar
        https://github.com/ah-OOG-ah/GregtorioOverlays/releases/download/1.1.2/goverlays-1.1.2.jar
        https://github.com/GTNewHorizons/worldedit-gtnh/releases/download/v0.0.8/worldedit-v0.0.8.jar

```

# Resource packs
### [GTNH Wiki Page](https://wiki.gtnewhorizons.com/wiki/Resource_Packs)

[
Modernity,<br>
Modernity-Fix,<br>
Modernity-GTNLResonaticCircuit
](https://github.com/ABKQPO/Modernity-GTNH/releases/tag/v1.5.9)

[Outlined Ores](https://github.com/Ranzuu/OutlinedOres-Modern/releases/tag/v.1.3)

[Shadow UI](https://github.com/Ranzuu/Shadow-UI/releases/tag/v2.8.X%2Fv4.30) (Optionally configure [coloredGUI, machineMetalGUI, and Waila](https://github.com/Ranzuu/Shadow-UI?tab=readme-ov-file#configuration-notice))

[AE2 Dark Mode](https://github.com/Ranzuu/AE2-Dark-Mode/releases/tag/v.1.9)

[Medium Large Turbine](https://github.com/DarkScorpyon/Medium-Large-Turbine/releases/tag/LargeTurbine) (Might not work without Modernity)

[Just Fire](https://github.com/Ranzuu/Shadow-UI/releases/tag/Just-Fire)
