# gimbal
Hardware and software for UAV Austin's homebrew gimbal.

Notes:
 - MPU two jst connectors align with 7 pin header connected to STM
   - SPI connections
 - Voltage Rgulator rated for 12-13V input. Outputs 3.3V up to 250 mA
 - CP2102 USB to UART converter
 - Boot0 and Boot1 in 3 and 4 pin arrangement for programming settings
   - Boot0 connects to either ground or PWR (3.3V)
   - Boot1  (PB2) connects to ground, PWR, or the motor controller
 - MPU goes on its own board seperate from the STM, DRV, CP2102, USB, and Voltage Regulator
 - Jumper to connect NRST to ground or external input voltage
 - PA13/14 jtag | PB4/5/6/7 SPI on STM
 - 2 sets of 2 header pins to get power from battery
   
