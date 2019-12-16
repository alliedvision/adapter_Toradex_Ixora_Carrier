# Allied Vision Adapter Board CSI-2 for Toradex Ixora Carrier Board

![toradex_ixora_adapter](/Images/Ixora_Adapter_Board.jpg)

This repository contains open hardware design files for an adapter board supporting the Allied Vision Alvium CSI-2 camera pinout to the Toradex Ixora Carrier Board, created by Allied Vision.
The board allows the user to interface with one Alvium MIPI CSI-2 compatible camera over a Flexible Flat Cable (FFC) connector.

This adapter can also be ordered at [Allied Vision](https://www.alliedvision.com/en/meta-header/contact-us/contact-sales.html) or a [qualified Allied Vision distributor](https://www.alliedvision.com/en/about-us/where-we-are.html) under order code **14908** - Adapter Board CSI-2 Toradex Ixora Carrier
.

## Getting Started

These instructions will get you a copy of the design files to make your own adapter boards for development and testing purposes. 
The board can be produced and assembled using the provided design files. Please take a look at the mechanical layers for more information regarding the PCB stackup recommended for fabrication. 

See our [website](https://www.alliedvision.com/en/support/technical-documentation/alvium-csi-2-documentation.html) for further documentation and installation guides of the finished boards.

### Prerequisites

* A running installation of Altium.
* A PCB producer & PCBA manufacturer or some soldering skills.
* One Toradex Ixora Carrier Board with an installed SOM
* One supported MIPI CSI-2 FPC cable
	* Allied Vision part numbers #12316, 12317, 12318
* [One Allied Vision Alvium CSI-2 camera](https://www.alliedvision.com/en/products/embedded-vision-cameras.html)

### Installing

Open the *CSI2-IXORA_Rev01.PrjPcb* project file in your Altium environment.

## Built With

* [Altium Designer 19](https://www.altium.com/altium-designer/de)
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
