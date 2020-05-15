# STM32F4_LIDAR
 
1. Description

Temperature/pression sensor BM280, working on STM32F4 Discovery. 
The values are continuously read by the sensor and sent with I2C to the STM32F4 microcontroller, which displays it in IAR with Live Watch. They may be further proceesd in C for user purpose. 

2. How to use

Dowload the whole content of the project.
Run the CubeMX file BM_280.ioc and generate project for IAR EWARM. Open the generated project, Download and Degug (Ctrl+R) in the STM board, then Go (F5).
In the Live watch field in IAR we may see the temperature, with an ad-hoc, approximate, calibration. User should use a proper calibration, as suggested by Bosch.

3. Software context

The project was verified using:

-STM32 Cube MX version 5.6.0

-Firmware package STM32Cube FW_F4 V1.25.0

-IAR-EWARM v 8.50.1.

Notice: For other software context, some modifications may be necessary, as the future evolution of these products is unknown.

4. Hardware context

-STM32F4 -Discovery, as with I2c on PB8 and PB9.

-BM280 module on I2C1 with GND and VIN coupled to GND and VCC.


5. Youtube classroom: to be posted
