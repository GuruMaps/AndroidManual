## Custom Map Sources

In addition to built-in online raster maps, Galileo Offline Maps also supports custom online maps. You can add any map source you like using a special XML file that contains description of map provider.

### Simple custom map sources {#simpleCustomMapSources}

The following example shows how the XML file for OpenStreetMap source may be defined:

```
<?xml version="1.0" encoding="UTF-8"?>
<customMapSource>
<name>OpenStreetMap</name>
<url>http://{$serverpart}.tile.openstreetmap.org/{$z}/{$x}/{$y}.png</url>
<serverParts>a b c</serverParts>
</customMapSource>
```

### Custom multi-layer map sources {#customMultiLayerMapSources}

Map sources which consist of two or more layers can be defined, similar to single-layer custom map sources. The following example shows how the XML file for OpenSeaMap hybrid source may be defined:

```
<?xml version="1.0" encoding="UTF-8"?>
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<customMapSource>
<name>OpenSeaMap</name>
<minZoom>0</minZoom>
<maxZoom>18</maxZoom>
<layers>
<layer>
<url>http://{$serverpart}.tile.openstreetmap.org/{$z}/{$x}/{$y}.png</url>
<serverParts>a b c</serverParts>
</layer>
<layer>
<minZoom>9</minZoom>
<maxZoom>18</maxZoom>
<url>http://tiles.openseamap.org/seamark/{$z}/{$x}/{$y}.png</url>
</layer>
</layers>
</customMapSource>
```

The most important tags of this definition are described below:

&lt;name&gt; – the name of the map source,

&lt;url&gt; – the path for the tiles of the map source with the specific placeholders in curly brackets:

* {$z} – the zoom level,  
* {$x} – the X tile coordinate,  
* {$y} – the Y tile coordinate,  
* {$invX} – the inverted X tile coordinate,  
* {$invY} – the inverted Y tile coordinate,  
* {$serverpart} – \(optional\) in case of multiple servers for the map source.  
* &lt;serverParts&gt; – a space-separated list of parts that replace the {$serverpart} in &lt;url&gt; tag.  
* &lt;retina&gt; – tag for defining the size of Retina map tiles:

* &lt;retina&gt;1&lt;/retina&gt; – for 512х512 px \(e.g. Google Maps HD\),
* &lt;retina&gt;2&lt;/retina&gt; – for 256х256 px \(e.g. CloudMade HD\).

**How to add**. There are several ways to add custom online map source to the app:
1. Place the XML file in the app shared folder in iTunes.
2. Open the XML file attached in Email on your device using the "Open in Galileo" option.
3. Open the XML file from Dropbox on your device using the "Open in.." option.
	
As a result, the new map source will appear in Map Source list.

**Troubleshooting**. Sometimes you can see empty map areas (tiles), with the following warning messages on the map:
* "_Tile loading error_. Please check your Internet connection" – this appears when tiles are missing in the cache and app can't download them. Enable an Internet connection or go to ’online’ mode to load the missing tiles.
* "_Tile loading error_. Wrong response from the server" – the online server is not responding. Try to navigate to this area later to reload any missing tiles.