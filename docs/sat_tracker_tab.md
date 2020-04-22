# MILSAT Vision - Documentation
> ### Satellite Tracker

Satellite tracker interface is tracking all the available satellites. The position, at geographic coordinate system, of the satellite is shown at the world map. 

![Satellite Tracker](img/sat_tracker_tab.png)

1. Icon of selected satellite at the world map
2. List of available satellites
3. Info of satellite parameters
   - Position at the world map: Latitude (LAT) and Longitude (LON)
   - Orbit Period - `time required to complete exactly one orbit`
   - [Azimuth and Elevation](https://www.celestis.com/resources/faq/what-are-the-azimuth-and-elevation-of-a-satellite/)
   - Altitude - `height above Earth's surface`
   - Estimated time of the next coverage over user's position
4. Local Configuration
   - Current date and time
   - User position at geographic coordinate system
5. Select button - `activates the satellite`
6. Find button - `finds a satellite in coverage, the activation message is shown`
   - Antenna dish is set to point into a direction of the satellite
   - If no satellite in coverage is found, USA 274 is selected
7. Antenna Tracker (antenna settings)
8. Autotrack button - `sets the antenna to point into a direction of the satellite`
9. Set button - `sets the antenna to point into a given direction`

**[Back to Index](index.md)**
