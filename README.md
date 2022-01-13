# Minecraft Java Edition 1.18 Custom Dimension Sample

Data pack – Minecraft Wiki
https://minecraft.fandom.com/wiki/Data_pack

Custom – Minecraft Wiki
https://minecraft.fandom.com/wiki/Custom

Dimension Generator Minecraft 1.16, 1.17, 1.18
https://misode.github.io/dimension/

## usage

1. Download or clone this repository
2. Place this repository or symbolic links as `<level-name>/datapacks/VanillaCustomDimensionDatapack/...`
3. Placement world data or symbolic links like `<level-name>/dimentions/minecraft/overworld_custom/region/...`
```
<level-name>
+-- datapacks
|   +-- VanillaCustomDimensionDatapack
|       +-- data
|           +-- minecraft
|               +-- dimention
|                   +-- overworld_custom.json
|                   +-- the_nether_custom.json
|                   +-- the_end_custom.json
+-- dimentions
|   +-- minecraft
|       +-- overworld_custom (custom/)
|       +-- the_nether_custom (custom/DIM-1/)
|       +-- the_end_custom (custom/DIM1/)
~~
+-- level.dat
```
4. Start the minecraft server `java -jar server.jar --forceUpgrade --eraseCache`

