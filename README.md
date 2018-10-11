Hybrix
=======
Hybrix – a 3D printer inspired by constructions of RebeliX and Prusa MK3. Licensed as GPLv3. 

This is basically a Rebelix with X and Z axis from MK3 as well as MK52 and MK3's extruder.

Make note that this repo combines sources from:

 - https://www.thingiverse.com/thing:1692666/files
 - https://github.com/prusa3d/Original-Prusa-i3/tree/MK3
 - https://github.com/RepRap4U/RebeliX

![RebeliX](Rebelix_render.png "Preview of assembled printer" )

Build
=====

To continue OpenSCAD has to be installed and available as `openscad` command.

* Make necessary changes to configuration.scad according to printer that prints the parts and available hardware. 
* Generate a calibration object by `make calibration`.
* Print generated calibration.stl and repeat the steps if unhappy.

When satisfied, run `make clean && make all`. That produces STLs with your tweeks.

