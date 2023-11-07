# Finding GIS Data

Some general advice for searching the Internet for GIS data, and some recommendations of top sites for specific types of data.

Compiled by Keith Jenkins <kgj2@cornell.edu>, GIS Librarian at Cornell Unversity's Mann Library.  Updated 2023-11-07

<https://cornell-gis.github.io/finding-gis-data/>


## Geolode
  - Start here: <https://geolode.org/>
  - Search/filter by place or broad topic
  - Global data is tagged as "Earth"

## Finding GIS Data via Google, etc
  - Try the obvious... search for something like: GIS data {placename}
  - Some places (like New York state) may have both a data website AND a geodata website
  - Data is created and managed at different administrative levels (country, state, county, city, etc.)
  - Try both the city AND the county (example, <https://geolode.org/?q=angeles> )

## Parcels
  - Often maintained at the county level, possibly state level.
  - There are many online map viewers that let you look at parcel boundaries and get info for specific addresses, but no way to download the whole dataset.
  - Sometimes there may be a separate website with downloadable data.  But other times, the county may only sell the data or may not make it available at all!
  - Map viewer example: <https://mapping-tompkins-tompkinscounty.hub.arcgis.com/>
  - Data download example: <https://tcdata-tompkinscounty.opendata.arcgis.com/>
  - Statewide parcels: <https://gis.ny.gov/parcels>

## OpenStreetMap
  - Most complete street dataset of the world (better than Google, Apple, Bing), but also has data for many other types of features.
  - Preview the data at <https://www.openstreetmap.org/>
  - Country-based shapefile downloads: <https://download.geofabrik.de/>
  - Search for specific features: <https://overpass-turbo.eu/>
  - Thematic extracts for city-sized areas: <https://export.hotosm.org/>
  - OSM can sometimes be a good source for many of the types of data listed below.  What data it contains is usually very good quality, but it is not necessarily complete for a given area.

## Building footprints
  - OpenStreetMap has a lot of buildings, but can be incomplete for many areas
  - Microsoft and Google have been using AI to extract building polygons from imagery
  - Microsoft: <https://github.com/microsoft/GlobalMLBuildingFootprints/#will-there-be-more-data-coming-for-other-geographies>
  - Google: <https://sites.research.google/open-buildings/>
  - Some places may have their own building inventories.

## Boundaries
  - GeoBoundaries has collected the best publically-available data for each country: <https://www.geoboundaries.org/>
  - US Census Shapefiles: <https://www.census.gov/cgi-bin/geo/shapefiles/>

## Transportation
  - Streets are often maintained at the state level
  - Complete layer vs major roads + minor roads
  - OpenStreetMap is the best choice for many countries

## Landcover
  - US NLCD (30m): <https://www.mrlc.gov/data>
  - US Cropscape (30m): <https://nassgeodata.gmu.edu/CropScape/> 
  - GlobCover (300m): <http://due.esrin.esa.int/page_globcover.php>
  - ESA WorldCover (10m): <https://viewer.esa-worldcover.org/worldcover/>

## Elevation
  - US NED 30m and 10m: <https://cugir.library.cornell.edu/?q=ned>
  - Global SRTM 90m: <https://dwtkns.com/srtm/>
  - Global SRTM 30m: <https://dwtkns.com/srtm30m/> (free NASA EarthData login required)
  - Higher-resolution data (1m to 5m) is occasionally available for some localities

## Hydrography
  - US NHD has streams, waterbodies, watersheds, etc: <https://apps.nationalmap.gov/downloader/#/>

## Business Points
  - AllThePlaces has location data for specific restaurant/store chains, scraped from company websites: <https://www.alltheplaces.xyz/>
  - To get point locations for all businesses in a given location, there are a couple websites that Cornell Library subscribes to.
  - Simply Analytics: <http://resolver.library.cornell.edu/misc/6168667>
  - Mergent Intellect: <http://resolver.library.cornell.edu/misc/8058953>

## Infrastructure
  - HIFLD has schools, hospitals, radio towers, rail crossings, public venues, etc.: <https://hifld-geoplatform.opendata.arcgis.com/>
  - Check HIFLD data for quality -- sometimes there are aggregation errors.  Sometimes local sources local sources are better or more recent.

## General advice
  - For other types of data, try Geolode, then try Google.
  - Try searching for `shp` instead of `GIS data`
  - Try including the term `download`
  - For countries where English is not the main language, search in the local language (example, Spanish `SIG datos`) and be sure to include any accents (`Sénégal`)
  - Specialized data (like NYC street/sidewalk curbs) that you've seen for one location may not be available for other locations.
  - Keep notes of where you download various files -- it's not always possible to figure out the source from the downloaded files.
  - Whenever possible, download any documentation or metadata at the same time you download the data.
  - Often there are multiple sources for the same data -- put it all on a map and compare specific locations, in terms of geometries as well as attributes.  Pick the data source that seems best for your project.
  - Keep looking!  But also know when to give up -- the data may not exist.
  - Feel free to ask for help if you get stuck: <https://guides.library.cornell.edu/gis/help>
