# 3Drag LDM extruder


This repository contain all the 3D model designed for the 3Drag 3D printer's extruder @ [+LAB](www.piulab.it).

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.4283444-blue)](https://doi.org/10.5281/zenodo.4283444)
![](https://img.shields.io/badge/CAD-fusion360-orange?logo=autodesk)
![](https://img.shields.io/github/license/piuLAB-official/3Drag_LDM_extruder?color=green)
![](https://img.shields.io/github/v/release/piuLAB-official/3Drag_LDM_extruder)

![](https://github.com/piuLAB-official/3Drag_LDM_extruder/blob/main/cover.png)

LDM (liquid Deposition Modeling) is a particular 3D printer process in which viscous fluid are extruded from a reservoir and deposited on the build plate. This process is also known as Direct Ink Writing (DIW).

The third version of the LDM extruder was developed with the porpuse of making a modular extruder, easy to assemble and disasseble.
- The syringe holder is stronger of the previour version and can be used to easily mount syringe from 10ml to 60ml.
- The extruder assembly is divided into three main parts. If one component broke you can easily switch is without disassembling all the extruder.
- The completely redesigned drive unit is stronger and smoother. The M8 screw has been substituted with a T8 lead screw. Two version are available with a 2:1 and 4:1 reduction. Higher reduction provide higher extrusion force and higher precision over the extruded material volume.
### Firmware mods needed:
- Change _DEFAULT_AXIS_STEPS_PER_UNIT_ for E motor according to the following equation: ![](https://latex.codecogs.com/svg.latex?Esteps/mm=\frac{motorSteps*microsteps*gearMultiply}{8})
- Set to dummy the E0 thermistor.
- Set to 20°C the minimum temperature for preventing extrusion.

[BOM](https://github.com/am-craft/3Drag_LDM_extruder/blob/main/BOM.md)

Previous version of the extruder are available at thingiverse: [version 1](https://www.thingiverse.com/thing:482873), [version 2](https://www.thingiverse.com/thing:4635819)
