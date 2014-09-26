UTouch library
==============

Version with modified examples to work with 3.5" TFT LCD from mcufriend.com using modified UTFT library from

Tested on Arduino MEGA clone and 3.5" TFTLCD for arduino 2560 from mcufriend.com

If you have problems - create issue on GitHub.

## Instalation
1. If you have installed original UTouch from Henning Karlsen, then first remove (or rename) UTouch frolder from Arduino Library folder
2. "Download":https://github.com/dgolda/UTouch/archive/master.zip the Master branch from gitHub.
3. Unzip and modify the Folder name to "UTouch" (Remove the '-master')
4. Paste the modified folder on your Library folder (On your `Libraries` folder inside Sketchbooks or Arduino software).

To test your touch screen:
* Open in Arduino IDE: Examples, UTouch, Arduino, UTouch_Calibration.ino

## Modification

No modifications in main library code.

Modifications in examples:
* changed TOUCH_ORIENTATION to LANDSCAPE
* change display model to NIC35WS in UTFT initialization (use ILI9327_8 driver)
* UTouch_Calibration prints calibration result to serial - just copy&paste to UTouchCD.h
