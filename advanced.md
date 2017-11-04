## Advanced

### Sync

Galileo allows you to sync your collections between all your devices \(Android and iOS\). The only thing you need to do, is login using your Facebook or Google account. Go to Settings &gt; Sync and choose one of these.

![](/assets/sync.png)

Consider to use same account on all devices which you want to sync Collections.

### Navigation

You can change language of navigation voice instructions, by choosing it in Settings &gt; Navigation &gt; Voice Instructions.

![](/assets/settings_navigation_language.png)

If preferable language is not supported by your default Text-To-Speech Engine \(TTS\) it will appear in light gray colour. In this case try to choose another TTS in System Settings &gt; Language & Input &gt;  Speech &gt; Text-to-speech output, or install the new one, which support your preferable language.

### Data Backup

Backing up data is a great way to minimize accidental data loss and restore the most important geodata on your device.  
**Create backup**. Tap Back Up My Collections button on Settings &gt; Data Backup screen to backup the collections within the app.  
Note: created backup only includes data from My Collections \(bookmarks and GPS tracks\), and it doesn't include downloaded and cached tiles.  
When the backup finished successfully, you'll see the name of the device along with the date and time the backup was created:

![](/assets/backup.png)

Save backup. Backups are stored on your device and will be removed automatically when the app is removed. To prevent data loss, we recommend to save your backups regularly.

* To save the backup on your computer, launch iTunes and copy it using the File Sharing option.
* To share backup via another application, tap the ![](/assets/icon_share.png) icon.

![](/assets/backup_share.png)

Restore from a backup. There are several ways to restore your data from backup:

* Select .gbackup file from any file manager installed and choose Galileo:

![](/assets/open_backup_file_manager.png)

* Select item from your cloud service \(e.g. in Dropbox app\) and choose Galileo:

![](/assets/open_backup_dropbox.png)

* Move .gbackup file to Internal Storage &gt; Galileo\_backups folder. All .gbackup files from this directory will be listed in Galileo. Go to Settings &gt; Data Backup and tap prefered backup.

Important: restoring from backup will remove all current bookmarks and GPS tracks in My Collections.

### Cache info

To switch between the map sources and select the map which is the best one for you, go to [Settings &gt; Map Source]().  
Map Refresh. To set how often to refresh cached map tiles, go to Settings &gt; Cache Info. All tiles older than selected time will be downloaded while browsing online.

![](/assets/cache_info.png)

**Cache Info**. All loaded map tiles will be automatically saved to your device's storage and can be managed in Settings &gt; Cache Info, so you can delete the tiles you no longer need if you want to free up storage space.

Read also: [Custom Map Sources]().

### Maps Storage

If your device supporting SD Card memory extension and one of your storages become insufficient you can change default Map Download Storage in Settings &gt; Maps Storage. After selection one of the available storages all downloaded Maps will be moved to selected one. Maps will be downloaded on the storage with the largest amount of free space by default. If you don’t see Maps Storage Settings your device might not support SD Card memory extension or SD Card is not present.

![](/assets/maps_storage.png)

### GPS Filtering

Galileo Offline Maps app supports GPS data filtering in Settings &gt; GPS Filtering.  
**Accuracy Threshold**. Filter by the minimum accuracy at which the new points will be accepted. New points will be added to GPS track while recording if the accuracy is lower than selected \(recommended value is 150 m\).

![](/assets/accuracy_threshold.png)

Example: You are recording your GPS track while walking around your neighbourhood and you have entered a supermarket. Tall walls, roofs and other obstructions can block the signal from GPS satellites and the device cannot determine your location accurately enough. You may enable the accuracy filter to set the required accuracy and ignore inaccurate GPS data. If the received signal has lower than the required accuracy, that point will not be recorded in the track.  
**Distance Threshold**. Filter by the minimum distance travelled before a new point will be recorded. New points will be added to GPS track while recording if the distance between them is greater than selected \(recommended value is 5 m\).

![](/assets/distance_threshold.png)

Example: You are recording your GPS track while jogging, then you meet a friend and stop to talk to him. As the GPS sends location coordinates every second, too many points will be recorded on the same spot while you are talking, and the recorded track will take up more space. You may enable the distance filter to ignore GPS points if they are too close to each other. New points will start recording as you exceed the distance selected in the filter.

### Units Format

To set the units system and coordinates format you would like to use within the Galileo Offline Maps, go to Settings &gt; Units Format.  
**Units system**. The following units of measure for distance and speed are available to select from:

* **km** — for kilometres & km/h,
* **mi** — for miles & mph,
* **NM** — for nautical miles & kts.

**Coordinates format**. In Galileo Offline Maps you can choose to represent your coordinates in any way you like. The coordinate format you select will be used to display all coordinates within the app. Here is an example of different coordinate formats for New York city follows:

* +40.730598, -73.986580 \(DDD.DDDDD\)
* 40°43'50.1" N, 73°59'11.6" W \(DDD°MM' SS.S"\)
* 40°43.835' N, 73°59.194' W \(DDD°MM.MMM’\)
* 40.73060° N, 73.98658° W \(DDD.DDDDD°\)
* 18TWL 85577 09345 \(MGRS\)

