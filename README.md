# class_project
GES 778 class project. Anacostia watershed census map.

Documentation
Use of class 12 - chloropeth demo - https://leenoah1.github.io/class_project

Purpose/Goals: Create interactive webmap of census demographic data in the Anacostia Watershed

Data Sources
- Link to Anacostia Watershed data from MWCOG (current employed organization.  Data used to clip to census.gov tract data): http://www.anacostia.net/maps/Data_download.html
- Maryland census tract data from census.gov: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2010&layergroup=Census+Tracts

Brief Description of Geoprocessing:
- clipped Anacostia watershed shapefile to census.gov Maryland tract shapefile
- recalculated population demographics of new tracts that were clipped by the watershed shapefile 
    - calculated new geometry (acres)
    - calculated new population numbers based on new tract geometry/area
    
    
Technical

1. Plot GeoJSON for clipped GeoJSON -- put it in a gist and link to it from your repo's README.md

Basemap slippy (leaflet) Gist link  - https://gist.github.com/leenoah1/c6cb58257f6069bfb9d1d305df36e621
                                        http://blockbuilder.org/leenoah1/c6cb58257f6069bfb9d1d305df36e621

2. Plot GeoJSON on top of a slippy map (zoomable map tiles)
3. Add interaction using data in the GeoJSON file












