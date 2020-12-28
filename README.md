# Analysis of Geodata using OpenStreetMap

### Data Source:  

Downloaded StreetMap data for DACH countries from server:

Austria : https://download.geofabrik.de/europe/austria.html  
Germany : https://download.geofabrik.de/europe/germany.html  
Switzerland : https://download.geofabrik.de/europe/switzerland.html

### Data Processing:  

Installing OSMConvert (https://markiliffe.wordpress.com/tag/osmconvert/) :  

``` sudo apt-get install osmctools ```

Converting .osm.pbf to .osm file:
```
$ osmconvert austria-latest.osm.pbf -o=austria.o5m
$ osmconvert austria-latest.osm.pbf -o=austria.osm
```
Converting .osm to geojson/json file:

