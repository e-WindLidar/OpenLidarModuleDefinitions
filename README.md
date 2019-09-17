# About this repository
This repository contains the definitions of the OpenLidar modules.

This includes information about the generic purpose of the modules and how implementations of the modules should be documented.

# How OpenLidar Works
OpenLidar is a concept for a modular wind lidar to enable collaboration and cooperation on device hardware and software.

![The OpenLidar system limits](OpenLidarSystemBounds.png)

## The OpenLidar Modular Architecture

![The OpenLidar modular wind lidar architecture](OpenLidarModules.png)

## The modules
There are 11 modules in OpenLidar. More details about each module are provided at the linked pages.
1. [Power](module_power.md): Power conversion and conditioning, current and voltage control
2. [Interlocks](module_interlocks.md): Safety interlocks & Safe operation of the laser and scanner
3. [Photonics](module_photonics.md) & Laser source, beam splitter, and detector
4. [Optics](module_optics.md) Beam forming and focusing
5. [Scanner](module_scanner.md) & Beam steering, position sensing
6. [Controller](module_controller.md): Manages the other modules; converts input commands to system actions.
7. [Communications](module_communications.md): Transfer data to/from the lidar device.
8. [Signal processing](module_signalprocessing.md): Converting Doppler shift to LOS velocity.
9. [Storage](module_storage.md): Data memory
10. [Housing](module_housing.md): Weather protection and environmental conditioning.
11. [Chassis](module_chassis.md): Physical carrier for the modules.

These definitions are not complete. We welcome feedback on the description of each module and the content of the files. If you have comments, please [open an issue](https://github.com/OpenWindLidar/ModuleDefinitions/issues).

# To provide feedback
Please [open an issue](https://github.com/OpenWindLidar/ModuleDefinitions/issues).

# Acknowledgements
The first module definitions and OpenLidar architecture were developed by Joshua Calafato, Katherine Maul, Frank Modruson IV, and Alan Yeh in 2015 as part of a student study project at the University of Stuttgart.

# References
For more information about the OpenLidar concept see 
- Ines Würth, Andrew Clifton, Florian Haizmann, Holger Fürst, Steffen Raach, Jennifer Newman, & Nikola Vasiljevic. (2017, June). OpenLidar in Action: Integrating a scanner module into a robust lidar. Zenodo. http://doi.org/10.5281/zenodo.3416356
- 

