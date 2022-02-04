# X5S_Marlin_1.1.8_Auto-Bed-leveling

This is a remix/derevitive Marlin firmware for the Tronxy X5S with Tronxy XY-08N Auto-leveling sensor
Marlin 1.1.8 for the TronXY X5S. Fully working!

This has all the improvements I have done to the stock 1.1.6.

If you want to stay on the bleeding edge of Marlin , this is for you.

The way CoreXY is implemented is different on 1.1.8. Your motors may be swapped. If you get inverse motion or swapped X/Y, invert the motor directions!

AUTO BILINEAR AUTO BED LEVELING added.
Improved homing , and jog speeds from LCD , particularly Z axis. Stock 4mm/s is far to slow
Increased Z max speed. 4mm/s is far to slow to prevent blobbing during Z moves. Max is now 35mm/s
Much improved encoder operation. It now works as expected. Single click for menu items, proper direction, and better multiplier operation when changing values.
EEPROM support enabled.
Filament change options enabled.
Better default Jerk settings.
Proper MAX positions.

Several other small changes.
I suggest executing a "RESTORE FAILSAFE" from the LCD to ensure proper default EEPROM values are loaded immediately after flashing.

IMPORTANT:
YOU NEED TO ADJUST THE Z-axis Offset otherwise the nozzle may crash into the printer's Print bed
You can Follow this Tutorial on Youtube : https://www.youtube.com/watch?v=Q5M7DvdMcew
To automatically level the bed you need to add "G29" without quotes in your slicer to your starting G-code
ORIGNALLY MADE by The_Wizard,
