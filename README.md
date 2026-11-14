# metro-manila-amenity-maps

This repository contains the building footprint polygons with fully-tagged amenity types.

## Collaborators
* Hyenne Lim (Drey037) + Jacob Group
* Jericho Reyes (jemire22)
* Daniel Pua (den1alr1ver)
* JP Helbing (iofas)
* Anthony Libut (tonishii)

## Current Tags
* Commercial
* Industrial
* Residential areas, including entrances to villages and condominiums;
* Institutional
* Transportation, including stations and terminals of existing mass transit
modes;
* Others

## Legacy Tags (used on Makati, Mandaluyong, and Manila)
The amenities are then categorized into types based on the following OSM tags:
* Health, including hospitals, pharmacies, and clinics;
* Finance, including banks and ATMs;
* Education, including high schools and universities;
* Security, including police offices and fire stations;
* Transportation, including stations and terminals of existing mass transit
modes;
* Grocery, including fast food establishments, supermarkets, and convenience
stores;
* Government offices, including public service branches;
* Shopping malls and recreational areas;
* Residential areas, including entrances to villages and condominiums;
* Miscellaneous amenities.

## Project Directory
```bash
  ├── Makati City/ # Contains point and polygon amenities
  │   ├── Makati_point.geojson
  │   ├── Makati_polygon.geojson
  ├── Mandaluyong City/
  ├── Manila City/
  ├── README.md
  ├── Taguig City/ # Contains polygon amenities only
  │   ├── Original Data/
  │   │   ├── Taguig_osm_amenities.geojson
  │   │   ├── Taguig_point.geojson
  │   │   ├── Taguig_polygon.geojson
  │   │   ├── Taguig_zoning.geojson
  │   │   ├── taguig_fully_tagged.zip
  │   ├── Taguig_polygon.geojson # Merged residential amenities
  │   ├── taguig_amenities_points.csv.zip
  │   ├── taguig_amenities_polygon.csv.zip
  │   ├── taguig_fully_tagged_manual.geojson.zip # Fully tagged and granulated dataset
  │   ├── taguig_point.geojson.zip
  │   ├── taguig_polygon.geojson.zip
```