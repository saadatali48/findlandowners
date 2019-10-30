# Finding Land Owners
QGIS Plugin for find the details of land parcel owners on which the pipeline layer will intersect.

# Demo
https://youtu.be/-gBSzgNL9lw

# Description
This plugin is developed for QGIS 3.0 + version. It takes pipeline layer, Parcel layer and Output csv directory as inputs. All the attributes of parcels that are intersecting with a pipeline are written into the csv along with that pipeline. 


# Software:
QGIS Version 3.8.3
pyqt5

# Input
Pipeline vector layer (shp, kmz etc.) [line Feature]
Parcel vector layer (shp, kmz, etc.) [Polygon Feature]
Browse Folder  [To save exported CSV]

# Note: Both layers must have same coordinate system

# Output
CSV File with Pipeline name and All attributes of intersecting parcels.
