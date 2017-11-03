# Interface Overview

* [Application Modes]()
* [Trip Monitor]()
* [Map Sources]()

## Application Modes

### Location button

The app works in multiple modes depending on number of taps on _Location_ button with the following sign ![](/assets/icon_gps.png). Your position is shown on the map as a blue marker when you are staying and as a blue arrow when you are moving:

![](/assets/map_location.png) ![](/assets/map_driving.png)

Tip: if your location cannot be determined precisely, a blue circle also appears around the location marker. The size of the circle depends on how accurately your location can be determined: the smaller the circle – the greater the accuracy.

### Tracking mode

To determine your current approximate location on the map and enable the **tracking mode**, tap once the _Location_ button:

![](/assets/icon_gps.png) → ![](/assets/icon_gps_act.png)

Once tracking mode is active, app tracks your position on map as you move. To exit the tracking mode, move the map.

### Driving mode

To enable the **driving mode**, double tap the _Location_ button:

![](/assets/icon_gps.png) → ![](/assets/icon_gps_act.png) → ![](/assets/icon_compas.png)

While in driving mode, the app will orient the map in the direction you are currently moving. If you stop moving, the map will be oriented by compass.

Note: the accuracy of the compass can be affected by magnetic or environmental interference \(e.g. the magnets in earbuds\) and compass may need to be calibrated from time to time. When the device displays the calibration alert, tilt the screen to move the red ball around in a circle.

### Location services

Every time you see this icon ![](/assets/icon_question.png), it means that your GPS cannot currently get information about your location. It may also appear when Location Services is disabled on your device.

Note: depending on your device and available services, Location Services uses a combination of cellular, Wi-Fi, Bluetooth, and GPS to determine your location. If you're not within a clear line of sight to GPS satellites, your device can determine your location using crowd-sourced Wi-Fi and cell tower locations.

## Trip Monitor

Trip monitor panel provides you all the necessary trip statistics while moving. If enabled, it will display such useful information as \(from left to right\):

![](/assets/trip_monitor_1.png)

* current speed
* altitude

While recording a GPS track it will additionally display \(from left to right\):

![](/assets/trip_monitor_2.png)

* distance traveled
* trip duration

To hide trip monitor panel from map view, go to app [Settings &gt; Show Trip Monitor]().

## Map Sources

To switch to another map to display, select Map Source menu in app settings. There are 4 types of maps you can use within the app:

* Offline vector map,
* Online raster maps,
* Offline raster maps,
* Imported map sources.

### Offline vector map

Vector map source is set by default. It uses data from OpenStreetMap. App visualise this data and display a map in readily comprehensible form.

Note: vector and raster are the two basic data structures for storing maps. Vector map is a set of map features expressed by different types of geometry: points, lines and polygons. While raster map is represented by square images, therefore vector maps are smaller than raster maps. Plus, vector map works faster and it is simpler to update and maintain, whereas a raster image will have to be completely reproduced \(e.g. when a new road is added\).

Read also: [Settings for Vector Maps]().

