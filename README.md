# COVID mask settings
### 3D print settings I have optimized for mass production of the 3DVerkstan faceshield on an Ender 3 Pro.  
### Disclaimer: This is intended to assist Chapman University affiliated personnel for charity purposes, and I am not liable for your printer imploding  

* Printer: Creality Ender 3 Pro with OctoPi and BLtouch self-leveling bed 0.4mm nozzle
* Slicer: Ultimaker Cura 4.5.0
* CAD Software: Autodesk Fusion360
* Filament: Matterhackers PRO PLA

In this repository, I have attached the STL and cura profile I used if you want to tweak the settings.  I have 2 versions: 
* fast and loose: decent quality for rapid speed.  some unsupported areas are a little rough
* slow and smooth: I recommend this one.  at 0.3mm layer height you can get it almost as fast as above.  

I also have 2 open source droplet containment box designs.
* the first one is mine: https://a360.co/2RrGePB  
* the second one is in the Flatpackv5 folder (from https://www.aerosolblock.org/)

Otherwise find the
plug-and-play g-code file here: https://drive.google.com/a/chapman.edu/file/d/1QBju7udUCOP3C-gHDJ0qYh54JztkdXBj/view?usp=sharing
* Note: if you dont have self-leveling, you need to remove the relevant g-code from the preamble in a text editor.

This can accomplish printing 35 Shield Frames in <30 hours, or 50 minutes per shield.  

The frames are easily cracked apart with a paint scraper, razor blade or metal spatula.  I recommend cracking apart the tips of the arms first.  

For people not using Cura slicer and want to copy the settings I used, but warning: mileage may vary.  

The **CRITICAL** slicer settings are as follows:
* Orientation: 90 degrees rotation from default (so mirror plane of the frame is parallel to x-axis) (yes this matters)
* Layer Height: 0.28 mm
* Wall Line Count: 5 
* Top Layers: 3
* Outer Before Inner Wall: NOOOOO
* Filter Out Tiny Gaps: Yes
* Fill Gaps Between Walls: No
* Infill Density: 5%
* Infill Pattern: Gyroid
* Connect Infill Lines: Yes
* Min Infill Area: 4 mm^2
* Print Temp: 210 C
* Build Plate Temp: 60 C
* Speed: 60 mm/s
* Support Placement: Everywhere
* Support Wall Line Count: 0
* Support Density: 10%
* Min Support Area: 10mm^2
* Build Plate Adhesion: Skirt
* IT IS VERY IMPORTANT YOU SET THE WALLS TO START FROM THE INSIDE FIRST AND MOVE OUTWARDS TO TAKE ADVANTAGE OF THE VERY SPARSE SUPPORTS

Here is the original design.  Make sure to use North American Version 
https://3dverkstan.se/protective-visor/protective-visor-versions/

contact me at c.stephen.moore@gmail.com with any feedback or questions
