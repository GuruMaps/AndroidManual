# Settings

> Galileo Offline Maps is available in a ready-to-use state and app settings should be considered as an optional and more advanced way of using the app. Settings let you configure app options, purchase additional features and manage geo data representation.

## Map Source {#MapSource}

To switch to another map to display, select **Map Source** menu in app settings. There are two types of maps you can use within the app: offline and online maps.

### Offline maps
						
Vector map source is set by default. Once you’ve downloaded it (**internet connection required**), it will be available offline.
Vector maps are detailed, smooth, fast and provide high-quality image rendered in real time on the device. It takes up less storage space than raster maps.

**Note**: you can also use your own maps in .sqlitedb and .mbtiles formats, previously created on a computer and then imported into your device. Such maps can be viewed offline even when your mobile device has no internet connection. However, any personal raster/tile maps will use considerably more space than vector maps you may install.

Read also: [Offline Maps Import](/04-tips-and-tricks-and-troubleshooting.md)
	 						 						
### Online maps
						
There is a list of built-in raster map sources available online:
				 						
* HikeBikeMap
* Humanitarian OSM
* OpenBusMap
* OpenCycleMap
* OpenStreetMap
* Stamen – Terrain (USA only)
* Stamen – Toner
						 						
Caching is always enabled – the app saves all recently viewed map images in your cache and keeps them available for offline usage. To save maps, navigate to the area you are going to visit and zoom-in to the lowest viewable level of detail while you have access to the Internet. The level of saved detail will reflect the zoom level you viewed.

Read also: [Cache Info](/03-settings.md#cacheInfo).
						 						
**Note**: map download speed can vary while using online sources, and depends on the speed of your Internet connection and the speed of the server from where the map is downloaded.

In addition to built-in online raster maps, Galileo Offline Maps also supports custom online maps. You can add any source you like using a special XML file that contains a description of map provider.

Read also: [Custom Map Sources](/04-tips-and-tricks-and-troubleshooting.md#customMapSources).

### Additional source

You can add more online map sources to Galileo here: https://ms.galileo-app.com/

## Vector Maps Settings {#vectorMapsSettings}

### Download Maps

Vector maps are available and free for download within the app:
 
<img src="/assets/download_maps.png" width="375" height="418" />

To **download a map of the selected country** tap the country name in Available Maps list:

<img src="/assets/item_map_to_download.png" width="375" height="51" />

* To **pause a download**, tap the cell with the country name tap it again to resume a download,
* To **go to downloaded map** tap the ![](/assets/icon_show_on_map.png) button,
* To **remove a map** swipe your finger across the country name from right to left, then tap the Delete button, or use the **Edit** button.

As OpenStreetMap data is constantly updated by thousands of volunteers around the world, map updates are available from time to time within the app. In Galileo app all vector map updates are free and distributed automatically. If there is an update for a downloaded map, you will see **Update** button near the downloaded map name:

<img src="/assets/update_downloaded_map.png" width="375" height="93" />

To **update all your downloaded maps** tap the **“Update All”** button in toolbar menu:

<img src="/assets/update_all_button.png" width="375" height="139" />


### Font and Languages {#fontsAndLanguages}

#### Font size 

You can configure Galileo to display all text on a vector map at a comfortable font size. To increase, decrease, or change the default font size, go to app Settings > Font and Languages.

#### Preferred language order

In some regions, objects on the map in addition to local names have names in other languages. A map will show the names on the first language in this list if exists. It may be useful for multilingual countries, such as Belgium where Dutch, French and German share official language status:

<img src="/assets/fonts_and_language.png" width="375" height="486" />


### Map Features \(**Points of Interest\)** {#mapFeatures}

In addition to the basic appearance settings, you can select the objects you wish to display on the vector map. Select only the objects that you want to display to keep the map tidy and uncluttered:

* Restaurants, cafes, fast foods
* Bars, pubs, clubs
* Beauty salons, hairdressers
* Entertainment, arts and culture
* Monuments, places of worship
* Tourist attractions
* Hotels, hostels, campsites
* Banks, ATMs, currency exchanges
* Parking, gas and service stations
* Hospitals, clinics, pharmacy
* Shopping malls, supermarkets
* Police, post offices, embassies
* Universities, colleges, schools
* Public transport stops
* Train and metro stations
* Building names and numbers


## Appearance Settings {#appearance}

The following group of settings is used to configure how the main map looks:

<img src="/assets/settings_appearance.png" width="375" height="332" />
  

### Show Trip Monitor {#showTripMonitor}
 
To hide trip monitor panel from the map view, turn off this option.

Read also: [Trip Computer](01-launching-the-application.md#tripComputer)

### Show Coordinates {#showCoordinates}

To enable the real-time display of coordinates on the map, turn this option on. If enabled, “crosshairs” will appear in the map’s center with coordinates and zoom level in the selected format.

<img src="/assets/show_coordinates.png" width="375" height="58" />

### Show Zoom Buttons {#showZoomButtons}

To make visible zoom control buttons on the map, turn this option on. If enabled, plus and minus zoom buttons will appear on the map:

<img src="/assets/zoom_buttons.png" width="63" height="131" />

### Show Bookmark Name

To display a bookmark name on the map, turn this option on. The bookmark view will change and the name of the bookmark will appear. The bookmark name can be changed to your preference:

<img src="/assets/bookmark_name_2.png" width="375" height="170" />


### Screen Auto-Lock {#screenAutoLock}

The screen of your device will be turned off automatically after a specified period of time to save on power.
Turn this option off if you want your device not to lock the screen while using the Galileo app.


## Default Settings {#defaultStyles}


#### Default track style

Selected style is a default line style for the newly recorded and imported GPS tracks (solid color/speed gradient/altitude gradient):

<img src="/assets/default_styles_1.png" width="375" height="117" />

#### GPS filtering {#GpsFiltering}

<img src="/assets/gps_filtering.png" width="375" height="170" />

Filters will be applied for new and imported tracks.

#### Accuracy Threshold

Filter by the minimum accuracy of the received points. Points that are on the outside of the filter value will not be displayed in the track.

#### Distance Threshold

Filter by the minimum distance between points of a recorded track. Points that are closer than the distance specified in the filter will not be displayed in the track.

Read more: [Track Details](02-features.md#TrackDetails)


#### Default bookmark category

Selected category is a default icon for newly created and imported bookmarks:

<img src="/assets/default_styles.png" width="375" height="416" />

## Advanced Settings {#advanced}

### Synchronization {#sync}

Galileo Offline Maps allows you to synchronize all your data to make your collections visible and available through all your devices using your Facebook or Google account.

App uses Facebook/Google login only for authentication, this does not let the Galileo post or share your data.

To enable synchronization feature, go to the app Settings > Sync and select the appropriate way to authenticate.

<img src="/assets/sync.png" width="375" height="402" />

### Navigation {#navigation}

#### Navigation Mode

Select the mode in which the route will be built.

* Online - internet connection required to build a route:

<img src="/assets/settings_navigation_1.png" width="375" height="173" />

* Online First - if there's no internet connection, the rout will be build using an offline navigation data (**downloaded navigation data required**):

<img src="/assets/settings_navigation_2.png" width="375" height="222" />

* Offline -  no internet connection required to build a route (**downloaded navigation data required**):

<img src="/assets/settings_navigation_3.png" width="375" height="222" />

**Note:** to download a map with navigation data you need to use "Online First" or "Offline" mode.

#### Voice Instructions

The default language for voice instructions you hear while navigating a route depends on the language your device is set to use.  
To change the language, select one from the Voice Instructions list:

**Note**: as the App uses text-to-speech \(TTS\) engine instead of pre-recorded audio, correct pronunciation depends on the TTS engine.

<img src="/assets/settings_navigation_language.png" width="375" height="414" />

### Data Backup {#dataBackup}

Backing up data is a great way to minimize accidental data loss and restore the most important geodata on your device.

#### Create backup

Tap Back Up My Collections button on Settings &gt; Data Backup screen to backup the collections within the app.  

**Note**: created backup only includes data from My Collections (bookmarks and GPS tracks), and it doesn't include downloaded and cached tiles.  
When the backup finished successfully, you'll see the name of the device along with the date and time the backup was created:

<img src="/assets/backup.png" width="375" height="53" />

#### Save backup

Backups are stored on your device and will be removed automatically when the app is removed. To prevent data loss, we recommend saving your backups regularly.

You can use cloud services (Dropbox, OneDrive, Adobe Creative Cloud, Google Drive, etc) to save them.

<img src="/assets/backup_share.png" width="375" height="299" />

#### Restore from a backup

There are several ways to restore your data from a backup:

* Select .gbackup2 file from any file manager installed and choose Galileo:

<img src="/assets/open_backup_file_manager.png" width="375" height="473" />

* Select item from your cloud service \(e.g. in Dropbox app\) and choose Galileo:

<img src="/assets/open_backup_dropbox.png" width="322" height="233" />

* Move .gbackup2 file to Internal Storage &gt; Galileo\_backups folder. All .gbackup2 files from this directory will be listed in Galileo. Go to Settings &gt; Data Backup and tap preferred backup.

**Note**: restoring from backup will remove all current bookmarks and GPS tracks in My Collections.

### Cache info {#cacheInfo}

#### Map Refresh

To set how often to refresh cached map tiles, go to Settings &gt; Cache Info. All tiles older than selected time will be downloaded while browsing online.

<img src="/assets/cache_info.png" width="375" height="403" />

#### Cache Info

All loaded map tiles will be automatically saved to your device's storage and can be managed in Settings &gt; Cache Info, so you can delete the tiles you no longer need if you want to free up storage space.


### Maps Storage {#mapsStorage}

If your device supporting SD Card memory extension and one of your storages become insufficient you can change default Map Download Storage in Settings &gt; Maps Storage. After selecting one of the available storages all downloaded Maps will be moved to selected one. Maps will be downloaded on the storage with the largest amount of free space by default. If you don’t see Maps Storage Settings your device might not support SD Card memory extension or SD Card is not present.

<img src="/assets/maps_storage.png" width="375" height="233" />

### Units Format {#unitsFormat}

To set the units system and coordinates format you would like to use within the Galileo Offline Maps, go to Settings &gt; Units Format. 
 
#### Units system

The following units of measure for distance and speed are available to select from:

* **km** — for kilometres & km/h,
* **mi** — for miles & mph,
* **NM** — for nautical miles & kts.

#### Coordinates format

In Galileo Offline Maps you can choose to represent your coordinates in any way you like. The coordinate format you select will be used to display all coordinates within the app. Here is an example of different coordinate formats for New York city follows:

* +40.730598, -73.986580 \(DDD.DDDDD\)
* 40°43'50.1" N, 73°59'11.6" W \(DDD°MM' SS.S"\)
* 40°43.835' N, 73°59.194' W \(DDD°MM.MMM’\)
* 40.73060° N, 73.98658° W \(DDD.DDDDD°\)
* 18TWL 85577 09345 \(MGRS\)

## Help {#Help}

#### Contact Us

If you have faced a problem - here you can contact Support via email (**internet connection required**).

