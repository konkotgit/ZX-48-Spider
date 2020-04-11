# ZX 48 Spider
## ZX Spectrum 48 clone built on the basis of the ZX Max 48 design.

The board is designed to fit into the standard ZX Spectrum 48k or ZX Spectrum + housing.

## Characteristic:

* ULA based on the CPLD system from the Altera Max7000 family (EPM7128SLC84),
* 48KB RAM,
* AY-3-8910 or AY-3-8912 sound system with stereo output,
* Kempston standard joystick interface,
* RGB video output,
* possibility of using a power supply with any polarity,
* ROM bank switch,
* board fully adapted for through hole mounting

## Compatibility

Tested interfaces:

* DivIDE, DivSD - work
* DivIDE + - not working
* Ti-of-TTL + FDD 35 clone works
* Beta disk 48k - works
* Beta disk 128k - works
* Tact-Polbasic - works
* D + - works
* Interface 1 + Microdrive - works, but RS232 does not work, because there is no 12V on the connector.
* (Interface II, AY and others without their ROM, work)

Thanks to Maryjan from speccy.pl forum for testing.

The software for the CPLD EPM7128 system was developed based on an implementation of OpenCores by Miguel Jodar. Don "Superfo" used this implementation to create the ZX Max family, on the basis of which the ZX 48 Spider was designed. Firmware in its current form was created with the active participation and help of speccy.pl forum members. This project uses CPLD from ZX Max 48 Issue 2


![ZX 48 Spider](/photos/zx48spider_rev1_1_small.jpg)