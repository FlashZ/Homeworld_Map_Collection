# Homeworld (1999) – Historic Multiplayer Map Collection  
*Preserving two decades of community creativity*

## About  
This repository is an **archive of fan‑made multiplayer maps for the original *Homeworld*** (1999, v1.05 GOTY).  
Many of these files circulated on relicnews.com, WON, and early clan websites in the 2000‑2005 era and are increasingly hard to find.  
Everything here is provided *as‑is* for historical and educational purposes.

## Directory layout
Maps/ # each sub‑folder is a self‑contained level

├─ Map_Name2/ # 2 player version

│ ├─ Map_Name.level # mission script

│ ├─ Asteroid.dist # resource distribution tables

│ ├─ DustCloud.dist

│ ├─ Tiny.dist

│ ├─ Mothership_0.missphere # player‑start spheres

│ ├─ …

│ └─ Description.txt # lobby blurb & default rules

├─ Map_Name4/ # 4 player version

├─ 2nd_Map_Name/

└─ …

### Installation

1. **Locate your HW install** – e.g. `C:\Sierra\Homeworld` (GOG/CD).  
2. Copy any desired map folder from `Maps/` into:
Homeworld\Data\MultiPlayer\```


No game files are overwritten; uninstall by simply deleting the folder(s).

### Compatibility

Release	Works?	Notes
Homeworld 1.05 GOTY	✅	Original target.
Homeworld Remastered (2015)	⚠️	Needs conversion (see tools/HWRM_port_guide.md).
Homeworld Classic Remastered (v1.0rc)	✅	Copy as above; ignore .leveldata warnings.

### Curation rules

Original author tags kept where present (see Description.txt)

### Contributing

Zip the entire map folder ( .level, .missphere, .dist, Description.txt)

Open a PR in maps/<MapName>/ or create an issue with a download link.

Include any known author / year / changelog info.

### License
All map scripts remain © their original creators.
This repository is a non‑commercial preservation project under the CC‑BY‑NC‑SA 4.0 umbrella where permissible; contact us if you need a file removed.

Fleet Command confirmed.
– Relic 1999
