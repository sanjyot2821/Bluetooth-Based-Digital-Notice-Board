# BLUETOOTH-BASED DIGITAL NOTICE BOARD

## Overview

The Bluetooth-Based Digital Notice Board is an embedded system project developed using the LPC2129 ARM7 microcontroller. The system enables wireless transmission and display of text messages on LED dot matrix displays through a Bluetooth connection. Messages sent from a smartphone are received by the microcontroller, stored in EEPROM, and displayed as scrolling text.

---

## Features

* Wireless notice transmission using Bluetooth
* Real-time message display on LED dot matrix
* EEPROM-based message storage
* Scrolling text display
* UART-based Bluetooth communication
* I²C-based EEPROM interfacing
* Automatic message retention after power loss
* Embedded C implementation

---

## Hardware Components

* LPC2129 ARM7 Microcontroller
* HC-05 Bluetooth Module
* AT24C256 EEPROM
* 8×8 LED Dot Matrix Displays (4 Units)
* 74HC164 Shift Registers
* 74HC573 Latch IC
* Power Supply Circuit
* Connecting Wires and PCB

---

## Software Used

* Embedded C
* Keil uVision
* Flash Magic

---

## Working Principle

The system continuously waits for incoming messages from a smartphone via the HC-05 Bluetooth module. When a message is received, the LPC2129 microcontroller processes the data through UART communication and stores it in the AT24C256 EEPROM using the I²C protocol. The message is then displayed as scrolling text across the LED dot matrix display. In case of a power interruption, the stored message is retrieved from EEPROM and displayed again when the system restarts.

---
## Demo Video



https://github.com/user-attachments/assets/395b0632-b9c5-42ec-a5a1-d57a7d7bcf2d




## Author

**Sanjyot Laxman Dake**

BE – Electronics & Telecommunication Engineering

VPKBIET, Baramati

**Major Project**

