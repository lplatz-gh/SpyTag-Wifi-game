# Summary Hardware
- Batteries connected in series
- No voltage regulator, batteries connected to global VDD via simple switch
- GPIO 15 is pulled to ground (disable boot from SD card)
- CH_PD is pulled to VDD (enable device)
- Button 1 shorts GPIO 0 to ground (enable serial programming)
- Button 2 shorts GPIO 12 to ground (user input)
- LED panels are driven off global VDD
- GPIO 2 is used as the data output for both LED panels.
It is connected to DIN of the first panel.
DOUT of the first panel connected to DIN of the second panel.
- External Antenna is used
