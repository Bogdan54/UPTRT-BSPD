# UPTRT-BSPD PCB Design (Version 1.1)
This repository contains the PCB design files for version 1.1 of the UPTRT-BSPD (Universal Prototyping Test and Race Tool - Brake System Plausibility Device) project. The UPTRT-BSPD is being developed for participation in the Formula Student competition.

## Overview
The UPTRT-BSPD is a brake system plausibility monitoring and control device designed to ensure the safe operation of the vehicle's braking system. This repository specifically holds the PCB design files for version 1.1 of the UPTRT-BSPD, which includes various improvements and enhancements over the previous version.

## Repository Structure
* PCB/UPTRT-BSPD_V1.1/: Contains the KiCad project files for the PCB design of version 1.1.
* PCB/UPTRT-BSPD_V1.1/schematic.pdf: Schematic diagram in PDF format.
* PCB/UPTRT-BSPD_V1.1/bom.csv: Bill of Materials (BOM) listing the components used.
* PCB/UPTRT-BSPD_V1.1/gerber/: Gerber files required for PCB manufacturing.

## Features and Enhancements
* Improved signal integrity through controlled impedance routing.
* Enhanced power distribution for improved stability and voltage regulation.
* Refined component placement to reduce signal interference and optimize thermal management.
* Updated component selection for improved performance and availability.
* Updated communication interface for enhanced compatibility and data exchange capabilities.

## Getting Started
To view or modify the PCB design, you will need to have KiCad installed on your system. Follow these steps to get started:

1. Clone this repository to your local machine using 
> git clone https://github.com/Bogdan54/UPTRT-BSPD.git
2. Open the KiCad project files located in the PCB/UPTRT-BSPD_V1.1/ directory.
3. Use <a href="https://www.kicad.org/">KiCad</a> to view or modify the schematic, layout, and component placement and for the simulation you will have <a href="https://www.ni.com/ro-ro/support/downloads/software-products/download.multisim.html#452133">Multisim 14</a>.
4. Generate the necessary output files, such as Gerber files, for PCB manufacturing.

## Manufacturing
To manufacture the UPTRT-BSPD PCB (version 1.1), follow these steps:

Review the manufacturing specifications in the documentation.
Generate the required Gerber files using the KiCad project.
Submit the Gerber files to your chosen PCB manufacturer.
Review the manufactured PCB for quality and ensure it meets the specified dimensions and specifications.

## Documentation
For detailed documentation of the PCB design, including the schematic overview, component selection, layout considerations, and manufacturing specifications, please refer to the documentation files provided in the repository.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLv3 License</a>.
