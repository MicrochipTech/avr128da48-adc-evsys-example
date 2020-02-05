# AVR128DA48 ADC EVSYS Example

This repository provides an Atmel Studio solution with a bare metal code example for ADC triggered via Event System. 

In the main loop, the program reads the differential value between the AIN4 analog channel (PD4 pin) and AIN3 analog channel (PD3 pin).

## Configurations

PC7 - Configured as input (on-board SW0)

PC6 - Configured as output (on-board user LED)

ADC0 - Configured in single conversion mode

VREF - Reference voltage for ADC0 set to 2.048V

## Required Tools 

Software: ATMEL Studio and AVR-DA Device Packs

Hardware: AVR128DA48 Curiosity Nano

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
