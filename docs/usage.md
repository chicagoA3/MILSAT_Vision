# MILSAT Vision - Documentation
> ### Usage

In order to make MILSAT Vision available in your mission, you have to place a module logic in [Eden Editor](https://community.bistudio.com/wiki/Eden_Editor) `System (F5) / Modules / Effects`. Then select a location of your terrain in the module settings, you can also input a user defined position at geographic coordinate system [LON, LAT] but `User defined` item in combobox must be selected.
 
After the mission start, the action menu (scroll wheel menu) `Run MILSAT Vision` is set to all clients with player's unit who has `ItemMap` and `ItemGPS` in their inventory. 

The next thing what must be present is, obviously an satellite antenna. The antennas from Arma 3: Contact DLC are supported.
```
NOTE: Supported config names
"SatelliteAntenna_01_Small_Black_F", "Land_SatelliteAntenna_01_small_mounted_base_F", "SatelliteAntenna_01_Small_Mounted_Black_F", "SatelliteAntenna_01_Small_Mounted_Olive_F", "SatelliteAntenna_01_Small_Mounted_Sand_F", "SatelliteAntenna_01_Small_Olive_F", "SatelliteAntenna_01_Small_Sand_F", "OmniDirectionalAntenna_01_sand_F", "OmniDirectionalAntenna_01_olive_F", "OmniDirectionalAntenna_01_black_F"
```

#### Establishing Satellite Link