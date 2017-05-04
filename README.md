# class_project
GES 778 class project.  Anacostia watershed census map. Population demographics by race


Documentation

Purpose/Goals: Create interactive webmap of census population/race demographic data in the Anacostia Watershed

Link to Anacostia Watershed data (used to clip to census.gov data): http://www.anacostia.net/maps/Data_download.html

data from census.gov
- https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2010&layergroup=Census+Tracts

Brief Description of Geoprocessing:
- clipped Anacostia watershed shapefile to census.gov Maryland tract shapefile.
- recalculated population demographics of new tracts that were clipped by the watersheds (based on geometry (acres))

Technical

Basemap slippy (leaflet) GIST link  - https://gist.github.com/leenoah1/c6cb58257f6069bfb9d1d305df36e621

