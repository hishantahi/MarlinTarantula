============================================================================

__Configured for MY Tevo Tarantula. It works for me, it may not work for you!__

See example_configurations/Tevo Tarantula for other Tarantula configurations:

- Tarantula-01
  - BLTouch, NO SD support, EEPROM enabled
- Tarantula-02
  - BLTouch, SD support, EEPROM enabled
- Tarantula-03
  - NO bed autolevel, SD support, EEPROM enabled
- Tarantula-04 (contributed by Roy Gilby)
  - BLTouch, SD support, EEPROM enabled, Thermistor for Genuine E3Dv6, Software PWM Layer Fan
- Tarantula-05 (contributed by Rob Flip)
  - SN04 probe, SD support, EEPROM enabled

To set the bed size (large or small) after copying the configuration files that are appropriate to your
printer, edit the "configuration.h" and look for these line:
```
// The size of the print bed
#define X_BED_SIZE 200
#define Y_BED_SIZE 200
```
Change the bed size values to match your bed.
  
Do you have a configuration for the Tarantula that is not covered above? Would
you like to share it with others by having it added to the above examples?
If so, please contact me at jb.github (at) rcairgallery (dot) com and we'll work something
out. (Note: Please do not contact me for support questions. I'm afraid I just do not have
the time for answering such inquiries. Best bet is to ask in the Tevo Tarantuala
Facebook group at https://www.facebook.com/groups/TEVO.3dprinter.owners/.)

Thanks!

============================================================================

# Marlin 3D Printer Firmware

[![Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg?branch=RCBugFix)](https://travis-ci.org/MarlinFirmware/Marlin)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)

<img align="top" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!

## Marlin 2.0 Bugfix Branch

__Not for production use. Use with caution!__

This branch is used to accumulate patches to the latest 2.0.x release version. Periodically this branch will form the basis for the next minor 2.0.x release.

Download earlier versions of Marlin on the [Releases page](https://github.com/MarlinFirmware/Marlin/releases).

## Recent Changes
- Add a Hardware Abstraction Layer (HAL) supporting current AVR platforms
- Planning a HAL for Re:Arm
- Planning a HAL for STM32

## Submitting Patches

Proposed patches should be submitted as a Pull Request against this branch ([bugfix-2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)).

- This branch is for fixing bugs and integrating any new features for the duration of the Marlin 2.0.x life-cycle.
- Follow the [Coding Standards](http://marlinfw.org/docs/development/coding_standards.html) to gain points with the maintainers.
- Please submit your questions and concerns to the [Issue Queue](https://github.com/MarlinFirmware/Marlin/issues).

### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)

## Credits

The current Marlin dev team consists of:
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - English
 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - English
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - English
 - Chris Pepper [[@p3p](https://github.com/p3p)] - English
 - João Brazio [[@jbrazio](https://github.com/jbrazio)] - Portuguese, English

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
