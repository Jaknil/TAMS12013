# Type A Machines Series 1 2013 Wood edition with Full Graphic Smart Controller 

## Cura settings for the printer
In the cura menus:
* Add a new printer, choose "Other" and "Type A Machines Series 1 2014"
* Then find "Manage printers", select "Type A Machines Series 1 2014" and press "Machine settings"
* This menu will pop up, change the  highlighted items according to this image:
![](img/settings.JPG)
* [Paste this code into the "start Gcode" box](start_g_code.txt)

Now you are ready to print using SD card on the Type A Machines series 1 2013 wood editon! 

# Firmware files (only needed if you upgrade/rebuild the printer)
In the marlin directory there is a version of the Marlin 1.1 firmware configurated to run on  Type A Machine Series 1 3D printers from 2013 (plywood frame) equipped with a [DiscountRepRap Full Graphics Smart controller with LCD display and SD card reader](http://reprap.org/wiki/RepRapDiscount_Full_Graphic_Smart_Controller).

This printer type has a RAMPS1.4 card but it is wired a bit different from the standard way so the pins had to be reconfigured to account for things like that the two Y-motors are connected to the connectors marked with Z, among other things. But this is all accounted for in the firmware, just upload it like you would any marlin installation but use these files.

## Pictures from the installation of the Smart Controller

![Installing the card](img/installing%20(1).JPG)
![Installing the card](img/installing%20(2).JPG)

