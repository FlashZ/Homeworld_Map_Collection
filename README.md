# Homeworld and Homeworld: Cataclysm – Multiplayer Map Collection
*Preserving two decades of community creativity*

## About
This repository is an **archive of fan-made multiplayer maps for the original *Homeworld* and *Homeworld: Cataclysm/Emergence*** (1999–2000, targeting v1.05 GOTY for HW1 and v1.00 for Cataclysm).
Many of these files circulated on relicnews.com, WON, and early clan websites in the 2000–2005 era and are increasingly hard to find.
Everything here is provided *as-is* for historical and educational purposes.

Thanks to [@Volans-SF](https://www.github.com/Volans-SF) for providing additional HW1 maps and all of the Cataclysm Maps.

## Directory Layout

HW1_maps/ # Each sub-folder is a self-contained level for Homeworld 1
```
├─ Map_Name2/ # 2 player version
│ ├─ Map_Name.level # mission script
│ ├─ Asteroid.dist # resource distribution tables
│ ├─ DustCloud.dist
│ ├─ Tiny.dist
│ ├─ Mothership_0.missphere # player‑start spheres
│ ├─ …
│ └─ Description.txt # lobby blurb & default rules
├─ Map_Name4/ # 4 player version
└─ …
```

CATA_maps/ # Homeworld: Cataclysm maps (same structure as above)
```
├─ Map_Name2/
│ ├─ Map_Name.level
│ ├─ Asteroid.dist
│ ├─ DustCloud.dist
│ ├─ Tiny.dist
│ ├─ Mothership_0.missphere
│ ├─ …
│ └─ Description.txt
├─ Map_Name4/
├─ 2nd_Map_Name/
└─ …
```

## Installation

1.  **Locate your *Homeworld* or *Cataclysm* installation directory.**
    *   Examples: `C:\Sierra\Homeworld`, `C:\GOG Games\Homeworld`, `C:\Sierra\Cataclysm`.
2.  **Copy any desired map folder** (e.g., `Map_Name2/`) from this repository's `HW1_maps/` or `CATA_maps/` into the correct subfolder within your game's installation:
    *   **For Homeworld 1 maps:** Copy into `[Your Homeworld Install Path]\MultiPlayer\`
    *   **For Cataclysm maps:** Copy into `[Your Cataclysm Install Path]\MultiPlayer\`

No original game files are overwritten. To uninstall a custom map, simply delete its folder from the `MultiPlayer` directory.

## Compatibility

| Release                             | Works? | Notes                                                    |
|-------------------------------------|--------|----------------------------------------------------------|
| *Homeworld* v1.05 GOTY              | ✅      | Original target for HW1 maps.                            |
| *Homeworld: Cataclysm* v1.00        | ✅      | Original target for Cataclysm maps.                      |
| *Homeworld Remastered* (2015)       | ⚠️      | HW1/Cata maps need conversion to work in HWR multiplayer. |
| *Homeworld Classic* (via Remastered) | ✅      | Copy as above; may show ignorable `.leveldata` warnings. |

## Curation Rules

*   Original author tags within `Description.txt` files have been kept where present.
*   The aim is to preserve maps as they were originally distributed.

## Contributing

We welcome contributions of additional classic Homeworld 1 and Cataclysm multiplayer maps!

1.  **Prepare your map:**
    *   Ensure the map folder is complete, containing the `.level` file, all necessary `.dist` and `.missphere` files, and a `Description.txt`.
    *   Zip the entire map folder (e.g., `MyAwesomeMap2.zip`).
2.  **Submit your map:**
    *   **Preferred:** Open a Pull Request, placing your map folder within the appropriate `HW1_maps/` or `CATA_maps/` directory.
    *   **Alternative:** Create an Issue and provide a download link to your zipped map file.
3.  **Provide Information:**
    *   Include any known details about the map: author(s), approximate year of creation, original website (if known), and any changelog or specific notes.

## License
All map scripts and associated files remain © (copyright) their original creators.
This repository is a non-commercial preservation project. Where original licenses are unknown or unstated, the collection is presented under a spirit similar to CC BY-NC-SA 4.0 where permissible for archival and community access.

If you are an original creator and wish for your map to be attributed differently or removed, please contact us by opening an Issue.

---
*Fleet Command confirmed.*  
*– Relic Entertainment, 1999*
