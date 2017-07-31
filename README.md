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
<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

## Marlin 2.0

With version 2.0, Marlin finally gets two long-planned improvements:
- A Hardware Abstraction Layer (HAL) that allows Marlin to target 32-bit architectures.
- A hierarchical code layout made possible by the most recent versions of Arduino IDE.

For complete Marlin documentation please visit the [Marlin Homepage <marlinfw.org>](http://marlinfw.org/), where you will find in-depth articles, how-to videos, and tutorials on every aspect of Marlin, as the site develops. For release notes, see the [Releases](https://github.com/MarlinFirmware/Marlin/releases) page.

## Stable Release Branch

This branch is a placeholder for the 2.0.x release, coming soon.

Previous releases of Marlin include [1.1.4](https://github.com/MarlinFirmware/Marlin/tree/1.1.4) (July 2017), [1.0.2-2](https://github.com/MarlinFirmware/Marlin/tree/1.0.2-2) (December 2016), and [1.0.1](https://github.com/MarlinFirmware/Marlin/tree/1.0.1) (December 2014). Any version of Marlin prior to 1.0.1 (when we started tagging versions) can be collectively referred to as Marlin 1.0.0.

## Contributing to Marlin

Click on the [Issue Queue](https://github.com/MarlinFirmware/Marlin/issues) and [Pull Requests](https://github.com/MarlinFirmware/Marlin/pulls) links above at any time to see what we're currently working on.

To submit patches and new features for Marlin 2.0 check out the [bugfix-2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x) branch, add your commits, and submit a Pull Request back to the `bugfix-2.0.x` branch. Periodically that branch will form the basis for the next minor release.

Note that the "bugfix" branch will always contain the latest patches to the current release version. These patches may not be widely tested. As always, when using "nightly" builds of Marlin, proceed with full caution.

## Current Status: In Development

Our main emphases are:
- Extending Marlin's supported architectures.
- Improving the organization and maintainability of the codebase.
- Integrating the most popular features from vendor forks.

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

## Marlin Resources

- [Marlin Home Page](http://marlinfw.org/) - The Marlin Documentation Project. Join us!
- [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin) - An overview of Marlin and its role in RepRap.
- [Marlin Firmware Forum](http://forums.reprap.org/list.php?415) - Find help with configuration, get up and running.
- [@MarlinFirmware](https://twitter.com/MarlinFirmware) on Twitter - Follow for news, release alerts, and tips & tricks. (Maintained by [@thinkyhead](https://github.com/thinkyhead).)

## Credits

The current Marlin dev team consists of:
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - English
 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - English
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - English
 - Chris Pepper [[@p3p](https://github.com/p3p)] - English
 - João Brazio [[@jbrazio](https://github.com/jbrazio)] - Portuguese, English
 - [[@teemuatlut](https://github.com/teemuatlut)]

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
