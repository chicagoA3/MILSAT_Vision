# MILSAT Vision - Documentation
> ### Radio Spectrum Analyzer

Radio spectrum interface is used for setting up and adjusting satellite frequencies. There are two frequency ports at the moment - the first is used as downlink for satellite image and the second contains downlink frequency for [SAR Radar](https://en.wikipedia.org/wiki/Synthetic-aperture_radar) as a part of [Future Imagery Architecture](https://en.wikipedia.org/wiki/Future_Imagery_Architecture) technology. The interface shows the status of system link, duplex emulation and processed signal.

![Radio Spectrum](img/sat_radio_spectrum_tab.png)

1. Frequency ports
   - F1 - Main frequency port for satellite view downlink
   - F2 - Second frequency port for SAR Radar downlink
2. List of available frequencies - `by selecting, the frequency is set as active`
3. Spectrum analyzer info
   - CT - Center Frequency is shown in spectrum analyzer as red vertical line
   - SP - Frequency Span
4. Antenna button
5. Mute button
6. SP Analyzer - Frequency settings
   - Gain and Threshold are automatically set to default values after antenna selection
   - Adjust within the range of gain and threshold to maintain satellite link open 
7. Selected frequency
8. [Bandwidth](https://en.wikipedia.org/wiki/Bandwidth_(signal_processing))
   - Available range is 10 MHz, 50 MHz, 250 MHz and 500 MHz