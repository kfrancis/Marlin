# Kris Waclawski's customizations for Marlin 3D Printer Firmware

![Customized Predator Marlin Builds](https://github.com/kfrancis/Marlin/workflows/Marlin%20Build/badge.svg?branch=2.0.x)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!

## Marlin 2.0.9.0

Marlin 2.0 takes this popular RepRap firmware to the next level by adding support for much faster 32-bit and ARM-based boards while improving support for 8-bit AVR boards. Read about Marlin's decision to use a "Hardware Abstraction Layer" below.

Download earlier versions of Marlin on the [Releases page](https://github.com/MarlinFirmware/Marlin/releases).

## What is this

I've taken Kris Waclawski's changes and I'm using git to make the process of updating from Marlin easier, getting those prebuilt configs made available to make the process of updating a Predator easier. 

### Currently Supported Pre-Builds (see buildconfigs directory)

* SKR 1.3 with TMC2208 and BTT TFT
* SKR 1.3 with TMC2209 and BTT TFT
* SKR 1.4 with TMC2208 and BTT TFT
* SKR 1.4 with TMC2209 and BTT TFT
* SKR 1.4 TURBO with TMC2208 and BTT TFT
* SKR 1.4 TURBO with TMC2209 and BTT TFT
* SKR v2.0 RevA with TMC2208 and BTT TFT [Careful, extra notes here](https://docs.google.com/document/d/1swmc4HvP9vxrxV2b9LVGa_I7GLTQGogQns7CfMYCckA/edit)
* SKR v2.0 RevA with TMC2209 and BTT TFT [Careful, extra notes here](https://docs.google.com/document/d/1swmc4HvP9vxrxV2b9LVGa_I7GLTQGogQns7CfMYCckA/edit)
* SKR v2.0 RevB with TMC2208 and BTT TFT
* SKR v2.0 RevB with TMC2209 and BTT TFT
* TRIGORILLA PRO (Stock Board)

## Look ma, no warranty

Seriously, make sure you know what you're doing if you're using these. I'm trying to be careful, but I make no guarantees. I don't own all these boards. I can only personally test the 1.4T with 2209's. Use your own judgement and seriously, buy Kris a coffee/beer already.