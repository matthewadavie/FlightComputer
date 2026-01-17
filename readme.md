# Flight Computer
This is a fun little project for a drone. Main goals are as below:
 - Powered by a LiPo battery (3S or 4S)
 - USB C for comms to uC (after flight?)
 - IMU, Magnetometer & GPS (because why not), barometer
 - Potentially BLDC motor control? Maybe a stretch goal but we shall see

 ## Parts List:
 - STM32 (uC)
 - U Blox SAM-M10Q (GPS)
 - Bosch Sensortec BMI088 (IMU, may change but I want to try the cool fancy new stuff)
 - Bosch Sensortec BMP390 (Barometer)

 ## Requirements
 - uC voltage: 3.3V
 - Comms: I2C
 