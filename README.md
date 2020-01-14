# West Yorkshire Mapping

[OpenStreetMap](http://www.openstreetmap.org/) is a fantastic open resource of mapping that can be re-used in projects under the Open Database License (ODBL). However, getting the data in a useable form isn't always straightforward. This repository contains a series of processed `.geojson` files created from a snap-shot of OpenStreetMap. The aim is to make it easy to get data for the specific object types you need.

The data are downloaded in the form of [a PBF file for West Yorkshire](http://download.geofabrik.de/europe/great-britain/england/west-yorkshire-latest.osm.pbf) [prepared by GeoFabrik](http://download.geofabrik.de/europe/great-britain/england/west-yorkshire.html). This master file is then processed using the command line tool `ogr2ogr` to create separate geojson files for different types (the sub-types are defined by the data in OSM itself) under the following main categories:

  * amenities
  * landusage
  * leisure
  * natural

## Cities

We've also created a subset of these GeoJSON files for Leeds, Bradford, and Calderdale.
