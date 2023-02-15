# USB-Cereal
USB-Cereal is a powerful, fully open source development tool that simplifies testing, development, debugging, and manufacturing of devices that utilize USB-C. Using USB-C’s extended capabilities this unique hardware saves time and effort through simplified debug and factory log capture, as well as firmware update procedures.

**Availability:** CrowdSupply campaign: https://www.crowdsupply.com/0xda/usb-cereal

**Documentation:** [This repo's wiki](https://github.com/oxda/usb-cereal/wiki).

**Repo structure**
- /docs [WIP] contains PDF schematics and usage instructions.
- /mcad [WIP] contains mechanical enclosure.
- /ecad [WIP] contains entire USB-Cereal project done in Altium.

**FT232RQ vs FT232RNQ vs CP2102N**
As FTDI chips have intermittent supply issues we have also qualified CP2102N for the application. This IC is widely available, and is generally equally well equipped and compatible with major OSes. 

# Important Notes
Initial release contains a mistake where CC1/CC2 pins are tied together and share a single 5.1k pull-down resistor. This causes the USB-Cereal to not be compatible with the full USB-C cables. 0xDA's devices have corrected this mistake, but please beware if you have forked the design earlier.

# License
All the work is licensed under Apache 2.0 license. Changes from the original project: BOM optimization, layout adjustments, addition of the CP2102N and FT232RNQ versions.
