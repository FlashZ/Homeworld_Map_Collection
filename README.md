# Homeworld (1999), Homeworld: Cataclysm/Emergence, and Homeworld: Cataclysm – Multiplayer Map Collection  
*Preserving two decades of community creativity*

## About  
This repository is an **archive of fan‑made multiplayer maps for the original *Homeworld* and *Homeworld: Cataclysm/Emergence*** (1999–2000, v1.05 GOTY and v1.00).  
Many of these files circulated on relicnews.com, WON, and early clan websites in the 2000‑2005 era and are increasingly hard to find.  
Everything here is provided *as‑is* for historical and educational purposes.

## Directory layout
HW1_maps/ # each sub‑folder is a self‑contained level
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

```
CATA_maps/ # Homeworld: Cataclysm maps (same structure as above)

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

## Installation

1. **Locate your HW or Cataclysm install** – e.g. `C:\Sierra\Homeworld` or `C:\Sierra\Cataclysm` (GOG/CD).  
2. Copy any desired map folder from `HW1_maps/` into:
    - Homeworld: `Homeworld\Data\MultiPlayer\`
    - Cataclysm: `Cataclysm\Data\MultiPlayer\`

No game files are overwritten; uninstall by simply deleting the folder(s).

## Compatibility

Release	Works?	Notes
Homeworld 1.05 GOTY	✅	Original target.
Homeworld: Cataclysm 1.00	✅	Original target.
Homeworld Remastered (2015)	⚠️	Needs conversion (see tools/HWRM_port_guide.md).
Homeworld Classic Remastered (v1.0rc)	✅	Copy as above; ignore .leveldata warnings.

## Curation rules

Original author tags kept where present (see Description.txt)

## Contributing

Zip the entire map folder ( .level, .missphere, .dist, Description.txt)

Open a PR in `maps/<MapName>/` or create an issue with a download link.

Include any known author / year / changelog info.

## License
All map scripts remain © their original creators.
This repository is a non‑commercial preservation project under the CC‑BY‑NC‑SA 4.0 umbrella where permissible; contact us if you need a file removed.

Fleet Command confirmed.
– Relic 1999
