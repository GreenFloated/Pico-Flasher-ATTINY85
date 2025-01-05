# PicoFlasher for ATTINY85

**PicoFlasher** is a project that enables the use of a Raspberry Pi Pico as an AVR In-System Programmer (ISP) to program microcontrollers such as the ATTINY85.

---

## Features
- Programming AVR microcontrollers using a Raspberry Pi Pico.
- Communication support via GPIO pins (MISO, MOSI, SCK, RESET).
- Easy configuration and flexible adaptation to other AVR chips.
- Support for LED indicators to signal the programmer's status.

---

## Hardware Requirements
- Raspberry Pi Pico with MicroPython firmware or another compatible setup.
- Target microcontroller (e.g., ATTINY85).
- Jumper wires for connections.
- Optional: LEDs with resistors for status indicators (Heartbeat, Error, Programming).

---

## Installation Instructions
1. Download the `.ino` file and appropriate libraries for the Raspberry Pi Pico.
2. Configure the Raspberry Pi Pico GPIO pins according to the "Connection Diagram" section.
3. Upload the code to the Raspberry Pi Pico using an IDE that supports MicroPython or the dedicated firmware.
4. Connect the ATTINY85 to the Raspberry Pi Pico as shown in the diagram below.
5. Execute the programming process.
---

## Supported Microcontrollers
- ATTINY85
- ATTINY45
- Other AVR chips supporting the ISP standard.

---

## Troubleshooting
- **No communication with ATTINY85:** Check the connections between the Raspberry Pi Pico and the microcontroller.
- **ATTINY85 power issues:** Ensure you are using the correct voltage (3.3V if the ATTINY85 operates in this mode).

---

## License
This project is distributed under the terms of the [BSD License](https://opensource.org/licenses/bsd-license.php).

---

## Acknowledgments
This project is based on open-source code and community support for Raspberry Pi Pico and AVR.

