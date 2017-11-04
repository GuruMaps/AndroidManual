## Offline Maps Import ##

Feature, available as an in-app purchase, allows you to import previously created custom offline maps in .sqlitedb or .mbtiles format.
**Creating an offline map**. The main idea is to create an offline map for the desired area in advance with one of the following tools on your computer using one of the following tools:

* [Mobile Atlas Creator](http://mobac.sourceforge.net/) (known also as MOBAC)
* [TileMill](https://tilemill-project.github.io/tilemill/)
* [SAS.Planet](http://sasgis.ru/sasplaneta/)

_Mobile Atlas Creator (MOBAC)_ – is free software that allows you to download maps from numerous map sources, and save them in the .sqlitedb format used by Galileo Offline Maps. This tool is compatible with Windows, Mac OS X and Linux.

Reference: to learn how to create offline maps in **.sqlitedb** format, please refer to the [MOBAC manual](http://mobac.sourceforge.net/quickstart/).
				
_TileMill (by MapBox)_ – is a desktop application for cartographers to quickly and easily design and create stunning offline maps in the .mbtiles format supported by Galileo Offline Maps. It is completely compatible with Mac OS X, Windows and Ubuntu.

Reference: to learn how to create offline maps in **.mbtiles** format, please refer to the [TileMill manual](https://tilemill-project.github.io/tilemill/docs/manual/).
					
SAS.Planet – is a program designed for viewing and downloading high-resolution satellite imagery and conventional maps in .sqlitedb format.
Reference: to learn how to create offline maps in **.sqlitedb** format, please refer to the [SAS.Planet manual](http://www.sasgis.org/wikisasiya/doku.php).
**Importing offline maps**. Once you have created an offline map, you should upload it to your device. There are two ways to import an offline map into your device: via iTunes or Dropbox.

**Using offline maps**. Go to Map Source in app settings and select the imported map name in the list and back to the map view. If you are not over the area with offline map, tap the green arrow indicating the direction to the offline map. Zoom in to see a detailed view of your offline map.
						
**Troubleshooting**. Sometimes you can see empty map areas, with the following warning messages on the map:
						
"_Tile is not in your offline map. Please add more layers._" – this means that there are no map tiles on the current zoom level in your offline map. You have probably imported insufficiently detailed levels, so when you zoom in there are no downloaded tiles for that level.