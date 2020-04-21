# MILSAT Vision - Documentation
> ### Satellite View

Satellite view interface can show satellite image only when the tracked satellite is in the coverage range and the satellite link is established. If one of the arguments is not met, the empty screen `ERROR! No data transmitted. There is not satellite coverage or the link is closed` is showed.

![Satellite view interface](img/sat_view_tab.png)

1. The bottom info bar shows:
   - Current UTC Time
   - Tracked Satellite
   - [Spatial Resolution](https://www.sciencedirect.com/topics/earth-and-planetary-sciences/spatial-resolution) (RES)
     - The spatial resolution for the satellite image in tablet interface is set to 5 meters, for better resolution the view must be switched to full screen 
   - Area of Interest (AOI)

2. View Filter

![View Filter](img/sat_view_filter.jpg)
- Thermal Infrared Sensor (TIRS) thermograph
  - Thermal vision - shade of red and green, bodies are white
- Thermal Infrared Sensor (TIRS) inverted
  - Thermal vision - black is hot
- Thermal Infrared Sensor (TIRS)
  - Thermal vision - white is hot
- Visible Spectrum (True Color)
  - Default
- [Operational Land Imager (OLI)](https://landsat.gsfc.nasa.gov/operational-land-imager-oli/)
  - Available only in full screen
- [Multispectral Scanner (MSS)](https://landsat.gsfc.nasa.gov/the-multispectral-scanner-system/)
  - Available only in full screen
- [Thematic Mapper (TM)](https://landsat.gsfc.nasa.gov/the-thematic-mapper/)
  - Available only in full screen


**[Back to Index](Index.md)**
