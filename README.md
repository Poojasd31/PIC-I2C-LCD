# PIC-I2C-LCD

Description:
This program demonstrates how to interface an LCD display (typically 16x2 or 20x4) with a PIC microcontroller using an I2C module (like PCF8574). Using I2C reduces the number of GPIO pins needed to just two pins:
SDA (Serial Data Line)
SCL (Serial Clock Line)
This makes the circuit simpler and cleaner compared to parallel LCD interfacing.

Key Features:
Displays text and numbers on LCD via I2C.
Can control cursor, clear display, and scroll text.
Compatible with PIC microcontrollers (e.g., PIC16F877A, PIC18F4550).
Reduces wiring and microcontroller pin usage.

Circuit Connections:

PIC Pin	I2C LCD Pin	Function
RC3	SCL	I2C Clock
RC4	SDA	I2C Data
VCC	VCC	+5V Power
GND	GND	Ground


Applications:
Displaying sensor data (temperature, RTC time, etc.)
Menu-based systems in embedded projects
Digital clocks and counters
Status displays in PIC-based devices
