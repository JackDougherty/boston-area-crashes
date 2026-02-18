# boston-area-crashes
testing crash maps for Boston - Brookline - Cambridge - Somerville

## arcgis-heat
- https://jackdougherty.github.io/boston-area-crashes/arcgis-heat/
- requires ArcGIS api key to show 2024 crashes from MassDOT GeoDOT only
- https://geodot.mass.gov/datasets/1ec67077233e460c98b60dda1ddc6598_0/
- same as 2024 crashes from MassGIS Data Hub
- https://gis.data.mass.gov/datasets/b42f2c990f784716b320ae0499886591_0/
- ArcGIS feature service > click Info button > I want to use this > select API

## hodv-heat
- https://jackdougherty.github.io/boston-area-crashes/hodv-heat/
- displays all compiled 2024 Boston area crash points, without filters
- based on [HODV heat template](https://github.com/handsondataviz/leaflet-heatmap)
- `data.csv` includes only *latitude,longitude* points with NO headers
- option to manually tweak radius and blur parameters for heat map display

## hartford
- https://jackdougherty.github.io/boston-area-crashes/hartford/
- based on Hartford crash template
- not yet working - data for all compiled 2024 Boston area crash points
