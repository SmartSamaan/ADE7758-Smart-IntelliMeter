# ADE7758-Smart-IntelliMeter
**Smart IntelliMeter: Three-Phase Bidirectional Energy Metering Evaluation/Development Board**<br />
Smart IntelliMeter is a 3-phase bidirectional energy metering development/evaluation board with an onboard STM8S207 controller. The board can interface a serial I2C display as well as an option for interfacing character LCDs (16x2, 20x2, 16x4, or 20x4) in 4-bit mode. The on-chip EEPROM of the controller is used to store the energy variables as well as calibration constants. The main features of the board are:<br />
•	STM8S207 controller with 32K Flash, 6K RAM, and 1K EEPROM<br />
•	An on-board 24MHz crystal for maximum processing speed of the controller<br />
•	USB Type-C port for serial communication between the board and PC to access measurement data on the PC.<br />
•	I2C port for serial interfacing of OLED displays (e.g., 0.96" or 1.3" OLED display or similar)<br />
•	4-bit interface for character LCDs (e.g., 16x2, 20x2, 16x4, 20x4 or similar)<br />
•	Additional I/O pins for ADC and other purposes<br />
The board includes ADE7758 24-pin SOIC which can also communicate via SPI communication with any external microcontroller unit to get the energy measurements. The technical specifications of the ADE7758 are:<br />
•	Highly accurate; supports IEC 60687, IEC 61036, IEC 61268, IEC 62053-21, IEC 62053-22, and IEC 62053-23<br />
•	Compatible with 3-phase/3-wire, 3-phase/4-wire, and other 3-phase services<br />
•	Less than 0.1% active energy error over a dynamic range of 1000 to 1 at 25°C<br />
•	Supplies active/reactive/apparent energy, voltage RMS, current RMS, and sampled waveform data.<br />
•	Two pulse outputs, one for active power and the other selectable between reactive and apparent power with programmable frequency
•	Digital power, phase, and RMS offset calibration.<br />
•	On-chip, user-programmable thresholds for line voltage SAG and overvoltage detections<br />
•	An on-chip, digital integrator enables direct interface-to-current sensors with di/dt output.<br />
•	A PGA in the current channel allows a direct interface to current transformers.<br />
•	A SPI-compatible serial interface with IRQ<br />
For more information, visit https://smartsamaan.com/<br />

## This repository contains the sample code and library required for the embedded development of this board. 
