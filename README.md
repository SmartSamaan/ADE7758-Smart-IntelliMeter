# ADE7758-Smart-IntelliMeter
**Smart IntelliMeter: Three-Phase Bidirectional Energy Metering Evaluation/Development Board**
Smart IntelliMeter is a 3-phase bidirectional energy metering development/evaluation board with an onboard STM8S207 controller. The board can interface a serial I2C display as well as an option for interfacing character LCDs (16x2, 20x2, 16x4, or 20x4) in 4-bit mode. The on-chip EEPROM of the controller is used to store the energy variables as well as calibration constants. The main features of the board are:
•	STM8S207 controller with 32K Flash, 6K RAM, and 1K EEPROM
•	An on-board 24MHz crystal for maximum processing speed of the controller
•	USB Type-C port for serial communication between the board and PC to access measurement data on the PC.
•	I2C port for serial interfacing of OLED displays (e.g., 0.96" or 1.3" OLED display or similar)
•	4-bit interface for character LCDs (e.g., 16x2, 20x2, 16x4, 20x4 or similar)
•	Additional I/O pins for ADC and other purposes
The board includes ADE7758 24-pin SOIC which can also communicate via SPI communication with any external microcontroller unit to get the energy measurements. The technical specifications of the ADE7758 are:
•	Highly accurate; supports IEC 60687, IEC 61036, IEC 61268, IEC 62053-21, IEC 62053-22, and IEC 62053-23
•	Compatible with 3-phase/3-wire, 3-phase/4-wire, and other 3-phase services
•	Less than 0.1% active energy error over a dynamic range of 1000 to 1 at 25°C
•	Supplies active/reactive/apparent energy, voltage RMS, current RMS, and sampled waveform data.
•	Two pulse outputs, one for active power and the other selectable between reactive and apparent power with programmable frequency
•	Digital power, phase, and RMS offset calibration.
•	On-chip, user-programmable thresholds for line voltage SAG and overvoltage detections
•	An on-chip, digital integrator enables direct interface-to-current sensors with di/dt output.
•	A PGA in the current channel allows a direct interface to current transformers.
•	A SPI-compatible serial interface with IRQ
For more information, visit https://smartsamaan.com/

## This repository contains the sample code and library required for the embedded development of this board. 
