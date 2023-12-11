info source: 
1) https://www.klipper3d.org/RPi_microcontroller.html
2) https://www.klipper3d.org/Measuring_Resonances.html?h=adxl
#######################################################################

- Make sure the Linux SPI driver is enabled by running sudo raspi-config and enabling SPI under the "Interfacing options" menu.

- Make sure the Linux I2C driver is enabled by running sudo raspi-config and enabling I2C under the "Interfacing options" menu. If planning to use I2C for the MPU accelerometer, it is also required to set the baud rate to 400000 by: adding/uncommenting dtparam=i2c_arm=on,i2c_arm_baudrate=400000 in /boot/config.txt (or /boot/firmware/config.txt in some distros).
