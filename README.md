# kicad-gamepaks

This repository contains KiCad symbols, footprints, board outlines and project templates for various Game Boy "Game Pak" cartridges. This includes the original Game Boy, Game Boy Color and Game Boy Advance. These models are abbreviated DMG, CGB and AGB respectively.

## Table of Contents

* [About kicad-gamepaks](#about-kicad-gamepaks)
  * [Symbol library](#symbol-library)
  * [Footprint library](#footprint-library)
  * [Project templates](#project-templates)
* [Gallery](#gallery)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contact](#contact)

## About kicad-gamepaks

### Symbol library

The `Connector_GameBoy.lib` symbol library (and accompanying `.dcm` symbol metadata file) found in `/library` contains three symbols that have pre-defined footprints assigned to them. There is a small difference between the AGB and DMG/CGB pinout.

* Game Pak AGB-002 edge connector
* Game Pak CGB-002 edge connector
* Game Pak DMG-09 edge connector

### Footprint library

The `Connector_GameBoy.pretty` footprint library found in `/modules` contains the following four edge connector footprints:

* Game Pak AGB-002 edge connector
* Game Pak AGB-002 edge connector (bootleg version)
* Game Pak CGB-002 edge connector
* Game Pak DMG-09 edge connector


### Project templates

The following project templates are provided, and all contain a schematic and board outline with an appropriate edge connector footprint to get you started. The board thickness is 0.8mm.

* Game Pak AGB-002
* Game Pak AGB-002 (short version)
* Game Pak AGB-002 (bootleg version)
* Game Pak AGB-002 (hybrid version, bootleg with original edge connector)
* Game Pak CGB-002
* Game Pak DMG-09
* Game Pak DMG-09 (short version)
* Game Pak DMG-09 (bootleg version)
* Game Pak DMG-09 (bootleg, short version)
* Game Pak DMG-09 (bootleg, ultra short version)

## Gallery

Below you'll find 3D previews of the templates included in this repository.

| Game Pak | PCB front| PCB back|
|---|---|---|
|DMG-09| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_back.jpg)|
|DMG-09 (Short)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_short_front.jpg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_short_back.jpg)|
|DMG-09 (Bootleg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_front.jpg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_back.jpg)|
|DMG-09 (Bootleg, short)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_short_front.jpg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_short_back.jpg)|
|DMG-09 (Bootleg, ultra short)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_ultrashort_front.jpg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_dmg-09_bootleg_ultrashort_back.jpg)|
| CGB-002| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_cgb-002_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_cgb-002_back.jpg)|
|AGB-002| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_back.jpg)|
|AGB-002 (Short)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_short_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_short_back.jpg)|
|AGB-002 (Bootleg)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_bootleg_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_bootleg_back.jpg)|
|AGB-002 (Hybrid)| ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_hybrid_front.jpg) | ![](http://jayvanhutten.com/kicad-gamepaks/pcb_agb-002_hybrid_back.jpg)|


## Getting Started

### Prerequisites

This project was made using KiCad 5.1.6. It is possible that you might have to upgrade to this version to be able to use all the files included in this repository.

Download the latest version here:
[https://kicad-pcb.org/download/](https://kicad-pcb.org/download/)


### Installation

There are several ways to include the symbol, footprint and project templates in your KiCad installation or projects. It mostly depends on where you want the files to live, which is a personal preference.

* Option 1
  * Merge the `/library` and `/modules` folder of this repository with your KiCad's library and modules folder. Make sure the libraries are also added in the Global/Project Specific Libraries settings of the Symbol and Footprint Editor.

* Option 2
  * Add the symbol and footprint libraries in KiCad via their respective editors by either clicking _File_, _Add library_, or by referencing the local copies of this repository's folders and/or files in your Global/Project Specific Libraries settings.


## Usage

Go to _File_, _New_, _Project from Template..._ to open up the Project Template Selector. Point "Template path" to the folder that contains the template files found in /`template` from this repository. Click the template that you would like to use and click "OK" to create a new project using the selected template.

![](http://jayvanhutten.com/kicad-gamepaks/templateselector.jpg)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/ 

## Contact

You can e-mail me at: ![email-address]


[email-address]: http://jayvanhutten.com/kicad-gamepaks/email-address.gif