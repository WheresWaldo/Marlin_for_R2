# Marlin for the Robo R2 printer
Current release Marlin modified for the Robo R2

In an effort to make the R2 an even better printer than it is, this is a newer version of Marlin than supplied by Robo3D. This version follows the version numbering scheme of the original Marlin source. The result is that this will always appear to be behind the "Official" firmware release as they are currently on version 1.1.8 (Marlin 1.1.0 RC6/RC8)

Settings will be optimized for what the actual R2 is capable of doing. 

Unified Bed Leveling (UBL) is the only leveling method enabled. As a result some of the Wizards found in RoboOS will not function and my make the UI non-responsive. As these are discovered they will be documented.

I will maintain a version with UBL enabled on the Robo3D forums. It is a simple change to Configuration.h to disable UBL and enable MESH.

# Known Issues

roboLCD Z Offset Wizard resets all EEPROM to factory defaults (do not use)
