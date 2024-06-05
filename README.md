<h1 align="center">
  <a href="https://github.com/ADanback/sql-for-data-analysis/tree/Geomapping"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/geo-maps.jpg" alt="geo-maps" /></a>
</h1>
<p align="center">
  <a href="http://geojson.org/"><img src="https://img.shields.io/badge/format-GeoJSON-e67e22.svg" alt="maps format" /></a>
  <a href="http://www.openstreetmap.org/"><img src="https://img.shields.io/badge/source-OSM-2ecc71.svg" alt="maps source" /></a>
  <a href="https://opendatacommons.org/licenses/odbl/1.0/"><img src="https://img.shields.io/badge/license-ODbL-2980b9.svg" alt="data license" /></a>
</p>
<br />
<p align="center">
  🗺 High Quality GeoJSON maps programmatically generated.
</p>
<p align="center">
  <sub>
    The only GeoJSON maps of the world you will ever need!
  </sub>
</p>

## Motivation
The purpose of this project is to **programmatically** extract maps from open
databases like [OpenStreetMap](https://www.openstreetmap.org) providing you
with a ready to use GeoJSON map that fits your needs.  

For each map you can click on the image to see a live preview.  
Please note that the previews show you the worst resolution available.  
See the details for higher resolutions.

All the maps are exported as GeoJSON and available to be downloaded directly as package on [npm](https://www.npmjs.com/org/geo-maps).  
See the details of each map for more information on how to get started.

Preview | Name | Short Description | Info Page
--------|------|-------------------|----------
<a alt="see countries-coastline on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-coastline.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-coastline.png" height="100px"/></a> | countries-coastline | Countries' political coastline borders | <a alt="See countries-coastline details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/countries-coastline.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>
<a alt="see countries-land on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-land.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-land.png" height="100px"/></a> | countries-land | Countries' political land borders | <a alt="See countries-land details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/countries-land.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>
<a alt="see countries-maritime on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-maritime.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/countries-maritime.png" height="100px"/></a> | countries-maritime | Countries' political maritime borders | <a alt="See countries-maritime details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/countries-maritime.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>
<a alt="see earth-coastlines on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-coastlines.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-coastlines.png" height="100px"/></a> | earth-coastlines | Earth's coastlines | <a alt="See earth-coastlines details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/earth-coastlines.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>
<a alt="see earth-lakes on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-lakes.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-lakes.png" height="100px"/></a> | earth-lakes | Earth's lakes | <a alt="See earth-lakes details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/earth-lakes.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>
<a alt="see earth-lands on geojson.io" href="http://geojson.io/#data=data:text/x-url,https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-lands.js"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/earth-lands.png" height="100px"/></a> | earth-lands | Earth's lands | <a alt="See earth-lands details" href="https://github.com/ADanback/sql-for-data-analysis/blob/Geomapping/info/earth-lands.md"><img src="https://raw.githubusercontent.com/ADanback/sql-for-data-analysis/Geomapping/media/details-button.png" height="50px"/></a>

## Conversion to other formats
If you need to convert maps in any of Shapefile, TopoJSON, CSV, SVG formats you can use the [mapshaper's web interface](mapshaper.org) to export the map in the format of your need.  


## Initial Authors of project
* **Simone Primarosa** - [simonepri](https://github.com/simonepri)

See also the list of [contributors](https://github.com/simonepri/geo-maps/contributors) who participated in this project.

## License
All data of this project is licensed under the [Open Data Commons Public Domain Dedication and License](https://opendatacommons.org/licenses/odbl/1.0/) as stated in [OpenStreetMap License](http://www.openstreetmap.org/copyright)

All source code of this project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
