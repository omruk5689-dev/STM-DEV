# STM32-DEV
<img width="2160" height="872" alt="3D_PCB1_2026-09-13" src="https://github.com/user-attachments/assets/3dbbd533-82b0-401f-92a7-56969ba2a4e9" />

STM32-DEV is a small STM32F103C8T6 development board built to make working with real device data feel simple. It's paired with a dashboard so you can actually see what your board is doing instead of digging through raw logs — designed with an easy, no-fuss approach to reading and understanding data as it comes in.

## Overview

Concept of the project
This project will allow you to plug in the board and view the dashboard right away. The project is designed for those who are interested in something fast and easy – no need in complex installation and configuration, no need in anything but the board itself and the figures you need.
## Hardware Features

The board itself is composed of several tried and true components:

A USB-C connector for power and communication that will save you from searching for the right cable. There is also an integrated 5V-to-3.3V LDO voltage regulator to provide a clean and stable power supply to the MCU. The central part is STM32F103C8T6, all the GPIO pins of which are available through pin-outs to connect any necessary circuitry. The board works with an 8 MHz clock source (crystal), together with a 32.768 kHz crystal for precise timing. There is a jumper selectable BOOT setting allowing fast and convenient switching between bootloader mode and regular operation mode. There is also a special SWD header to make firmware upload and debugging easy. The board also has a debounced reset button for convenient resetting of the device and two onboard status LEDs showing the current state of the board. Power rail 3.3V is supported by a set of decoupling capacitors, and two 20-pin headers expose the power, GPIO, and communication lines.


##SOFTWARE USED

EasyEDA Pro

##LICENSE

  MIT

