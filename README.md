# FlightGear custom scenery of Buenos Aires area 
---
This scenery covers some parts of the Buenos Aires province area (in the tile w060s40) and is generated using ![OpenStreetMap](https://www.openstreetmap.org/) data.

The process exctracts landcover information from the OSM datasets (landuse, natural, water tags, etc) and uses ![Osm2City](https://osm2city.readthedocs.io/) for line data and objects (roads, tracks, rivers, buildings, pylons, etc.)

A view of Puerto Madero in Buenos Aires:
<img src="/puerto madero.png" alt="Puerto Madero" />


## How to use

Clone or download and unzip, then add the folder as a scenery folder in FlightGear.

#### From command line

Use the `--fg-scenery` option:
```
fgfs --aircraft=ufo --airport=SADF --fg-scenery=/home/julio/repos/scenery-6040
```
#### Startup Script

Add it to your .fgfsrc script, normally located in your home directory or folder:
```
...
--fg-scenery=/home/julio/src/scenery/osm-2018/auto/output/
...
```

#### Launcher
If you use the FlightGear gui launcher, add the folder into `Add-ons->Additional scenery folders` using the Add(+) button on the right.  **DO NOT** use the `Install add-on scenery` button! That button its intended for scenery *packages*, not folders. 


See my rants about FlightGear in my ![blog](http://fg.bartatech.net/)
