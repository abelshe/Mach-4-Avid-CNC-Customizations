# Mach 4 Avid CNC
 

Customizations for the default Avid profile in Mach 4.

### Cycle Start Check
This is a basic check that ensures the Gcode file is on line 1. If it isn't, the user is prompted to continue. Stopping a cycle or eStopping doesn't rewind the GCode file, and I would not remember to rewind it before hitting cycle start. This caused some air cutting without the spindle being on. To prevent this, the user is explicitly prompted if they really want to cycle start.

### Feed Rate Sliders
**TODO**: Change the feed rate to sliders, as the inc/dec buttons are terrible. Tormach's PathPilot does this and is way better to fine tune the rates.
	



## Resources


Corbin's Blog: [https://www.corbinstreehouse.com](https://www.corbinstreehouse.com)

CNC Files: [https://www.corbinsworkshop.com](https://www.corbinstreehouse.com)