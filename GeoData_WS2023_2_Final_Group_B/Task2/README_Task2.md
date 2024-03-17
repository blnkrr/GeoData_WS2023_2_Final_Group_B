What have been done to finalize the project?


TASK 2.1
1. By the help of a plugin called Freehand Raster Georeferencer it was easier for us to georeference the map has been given to us.
2. By using plugin we located the map and found unique similarities between maps.
3. Afterwards by using georeferencing tool in the under of Layer segment we pointed special similarities between maps and as a result QGIS easily calculated the place of the map that needs to be georeferenced.
Layer > Georeferencer> Open Raster> Upload Burial_Mounds.png > 6 points selected by using founded similar points > transformation settings > browse output> start georeferencing 
TASK 2.2
1.By using the hillshade tool under he segment of raster-analysis we were able to make hillshade model with the help of the .tif file that has been provided us. Specieal settings has been made to get desired hillshade model.
REPLİES REGARDİNG TO QUESTİON;
Hillshade model significantly provided more detail and information than georeferenced map. Espacially for geostructure of the area.
Raster > Analysis > Hillshade > DTM file as input > Z factor 10 > Gereferenced map transparancy %60 top of the hillshade model.
Task2.3
1.With the help of Profile tool plugin we were easily measured the typical elevation of the area.
2. We simply opened the tool and measured between the lighter and darker area(The most constrated places). Since DTM file can give information about elevations in the area DTM(Digital Terrain Model) file was a must to have.
Plugins > Profile tool > Terrain Profile > Select DTM layer > Add layer > Drawing the line the is being desired to measure
We found the typical elevation as 1.80, 1.53 and 1.65.

TASK 2.4
1. By changing the hillshade models Azimuth parameter to 45 (to orient it) we can identify anomalies in the hillshade model.
2. To able to draw something or spot a place in QGIS we need to first create a new Geopackage layer and then edit it. By this way we can create spot these places.
We saw 3 unnatural rectangular places, since this place is old and we researched the area on internet we are believing these places can be Roman Forts.
Layer> Create Layer > New GeoPackage Layer (Geometry Type = polygon) > Add polygon
The geopackage can be dound in the Task2.4 folder.


