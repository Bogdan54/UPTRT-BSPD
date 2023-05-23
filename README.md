# UPTRT-BSPD PCB Design
This repository contains the PCB design files for the UPTRT-BSPD (Polytehnic University of Timișoara Racing Team - Brake System Plausibility Device) project. The UPTRT-BSPD is being developed for participation in the Formula Student competition.

## Overview
The UPTRT-BSPD PCB is designed to provide brake system plausibility monitoring and control functionalities. The PCB incorporates a microcontroller, flip-flop components, potentiometer, and connectors for external connections. The design ensures reliable and efficient performance while meeting the requirements of the Formula Student competition.

## Repository Structure
* PCB/Using 74HC74N with potentiometer/: Contains the KiCad project files for the PCB design.
* PCB/Using 74HC74N with potentiometer/schematic.png: Schematic diagram in PNG format.
* PCB/Using 74HC74N with potentiometer/bom.csv: Bill of Materials (BOM) listing the components used.
* PCB/Using 74HC74N with potentiometer/gerber/: Gerber files required for PCB manufacturing.

## Getting Started
To view or modify the PCB design, you will need to have KiCad installed on your system. Follow these steps to get started:

1. Clone this repository to your local machine using  
> git clone https://github.com/Bogdan54/UPTRT-BSPD.git
2. Open the KiCad project files located in the PCB/Using 74HC74N with potentiometer/ directory.
3. Use <a href="https://www.kicad.org/">KiCad</a> to view or modify the schematic, layout, and component placement and for the simulation you will have <a href="https://www.ni.com/ro-ro/support/downloads/software-products/download.multisim.html#452133">Multisim 14</a>.
4. Generate the necessary output files, such as Gerber files, for PCB manufacturing.

## Manufacturing
To manufacture the UPTRT-BSPD PCB, follow these steps:

1. Review the manufacturing specifications in the documentation.
2. Generate the required Gerber files using the KiCad project.
3. Submit the Gerber files to your chosen PCB manufacturer.
4. Review the manufactured PCB for quality and ensure it meets the specified dimensions and specifications.

## Documentation
For detailed documentation of the PCB design, including the schematic overview, component selection, layout considerations, and manufacturing specifications, please refer to the documentation files provided in the repository.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLv3 License</a>.
