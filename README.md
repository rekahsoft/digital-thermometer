# Simple Digital Thermometer (using [AVR-lcdLib][])

A simple digital thermometer with character LCD display, intended as an example project showing
how to use [AVR-lcdLib][].

Note however, that this project is not yet complete, namely the pcb is not yet completed. See
[Issues](#issues) and/or [Roadmap](#road-map) for more details.

* [Features](#features)
* [Tools](#tools)
* [License](#license)
* [Building](#building)
  * [Hardware](#hardware)
  * [Software](#software)
* [Issues](#issues)
* [Road Map](#road-map)

## Features <a name="features"></a>

- Uses a LCD character display to show the current temperature in Celsius or Fahrenheit using [AVR-lcdLib][]
- Uses TMP36 temperature sensor to provide +-2 degrees Celsius accuracy
- Has single toggle button to switch between Celsius and Fahrenheit (not yet implemented in firmware)

## Tools <a name="tools"></a>

This project wouldn't be possible without the following great open source tools:

- AVR-GCC, [AVR-libc][], and AVR-binutils which form the compiler toolchain that makes open
  source development for AVR microcontrollers possible.
- [avrdude][] to do in system programming of the AVR microcontrollers
- [Gnu Emacs][], because how else would I enter text?

## License <a name="license"></a>

Code licensed under ([GPLv3][]. Please see the LICENSE file for full details.

## Building <a name="building"></a>

### Hardware <a name="hardware"></a>

Currently, as mentioned above and in [Issues](#issues), the PCB is not yet developed, though a
circuit diagram is provided. It can be opened with kicad and is located within the
'DigitalThermometer' folder.

### Software <a name="software)</a>

## Issues <a name="issues"></a>

Currently, the pcb has not been completed, but the hardware design has been built on a
breadboard and tested with the current code, which found both to be functioning.

Additionally, the firmware does not currently support having a button to toggle between
displaying the temperature in Celsius or in Fahrenheit.

## Road Map <a name="road-map"></a>

- Design a PCB
- Add support for Celsius/Fahrenheit toggle button in firmware


[AVR-lcdLib]: http://git.rekahsoft.ca/AVR-lcdLib
[AVR-libc]: http://www.nongnu.org/avr-libc/
[avrdude]: http://savannah.nongnu.org/projects/avrdude
[Gnu Emacs]: http://www.gnu.org/software/emacs/
[GPLv3]: https://www.gnu.org/licenses/gpl.html
