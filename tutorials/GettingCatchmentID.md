# How to get Catchment ID for hospital locations

## Using QGIS

- Get NHDPlus12 Catchment from [NHDPlus HR](https://viewer.nationalmap.gov/basic/?basemap=b1&category=nhd&title=NHD%20View)
    - Search for Houston, TX
    - Check Watershed Boundary Dataset (WBD)
    - Check HU-2 Region
    - Click Find Products
    - Download USGS Watershed Boundary Dataset (WBD) for 2-digit Hydrologic Unit - 12 shapefile

- Clip the whole region for CMOC counties with "Extract/clip by extent"

- Find "Intersection" between hospital locations in shapefile and the clipped region.

- CatchmentID is shown in FEATUREID column

## Using Python 3
