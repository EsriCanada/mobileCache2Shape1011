mobileCache2Shape1011

Export Mobile cache to shapefile.

This code is updated for Mobile 10.1.1 (3320) and compiled as x86 to make it work on 64 bit machines

NOTE: You need Visual Studio 2008 to compile this version on your PC before to be able to use it !

This MobileCacheTool can extract selected features or features in a specified status (original/added/deleted/modified/current) to a shapefile. Photos saved in raster/blob fields are exported as files.

This version works for ArcGIS Mobile 10.x cache. (other versions are available at http://www.arcgis.com/home/search.html?q=mobile%20cache%20shapefile&t=content) This tool relays on ArcGIS Mobile 10.1.1 runtime and ArcGIS Desktop 10.1.1 runtime (need to have both mobile and desktop installed). In mobile10, esri.arcgis.mobile.dll is not installed to GAC, to run this tool, esri.arcgis.mobile.dll needs to be in current folder.
