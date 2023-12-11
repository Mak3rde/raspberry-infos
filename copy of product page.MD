######################################################################################################################################################
######################################################################################################################################################

Since tehthe website seems to be offline or not reachable more often this is a copy of the eleduino online shop.

DIRECTLY COPIED from : http://www.eleduino.com/7-0-Inch-1024x600-Pixel-IPS-Hdmi-Input-Capacitive-Touch-Screen-Support-Raspberry-pi-Banana-Pi-Pro-Be-p10533.html

######################################################################################################################################################
######################################################################################################################################################

The touchscreen can support Pi 3 Now ！only just edit config.txt for setting resolution or use we provide config as below URL,make sure the the power supply is 5V 2.5A for Pi or extal power for touchscreen.

This 7.0 inch Hdmi input capacitance screen touch screen lcd use more widly，support raspberry pi 2B、B/B+、banana pi 、banana pro 、beaglebone and you can also use it as a computer monitor just like any other general HDMI screen (not support touch function) for respberry pi. The solution is 1024*600, much better touch response, larger viewing angle, faster response time than resistive touch screenWe diy a bracket to the screen，make your pi to be a really Integrated Computer..The screen has the protective film in order to protect it shipping safe ，you can remove it when use it.

If you choose to use a distribution(Raspbian/Ubuntu/win10 Iot) from the Raspberry Pi Website in place of our  pre-  compiled distributions, you only should locate the “config.txt” file we provided, then replace the original “conf  ig.txt” file and save. It can work properly.

The best simple way is add the follow line to the end of the config.txt：

hdmi_group=2
hdmi_mode=1
hdmi_mode=87
hdmi_cvt 1024 600 60 6 0 0 0
max_usb_current=1

saved and reboot.

Version1.2 Features： 

●7.0-inch TFT screen display, 1024x600 Resolution

●capacitive touch screen, IPS full view 

●USB touch and power supply

●HDMI input

●Powered by USB，5V@1A

●Supports Raspberry Pi(Raspbian/Ubuntu/Win 10 Iot), BB Black(Angstrom), Banana Pi / Banana Pro(Raspbian/Ubuntu ),all img we will provided

●Not only for mini-PCs, it can work as a computer monitor just like any other general HDMI screen (win7、win8、win 10 is available)

●Lcd driver IC: ILI9486L
●Refresh rate：60HZ 
● Lcd Size ：188mm*107mm
Version1.2 user guide : download

Version1.2 all img ：download

Raspbian and Ubuntu config file : download

win 10 Iot config file : download


Version1.1 Features： 

●7.0-inch TFT Resistive touch screen display, 1024x600 Resolution 

●HDMI input 
●Powered and touch by USB

●Powered by USB，5V@1A
●Supports Raspberry Pi(Raspbian/Ubuntu), BB Black(Angstrom), Banana Pi / Banana Pro(Raspbian/Ubuntu )all img we will provided

●Not only for mini-PCs, it can work as a computer monitor just like any other general HDMI screen (touch function is unavailable in this case) 
●Lcd driver IC: ILI9486L
●Refresh rate：60HZ 
● Lcd Size ：188mm*107mm

Version1.1 user guide : download
Version1.1 all img ：download


Package Content： 

7 inch(1024x600)Touch Screen LCD Display x1

UBS cable x1
Customized shell for lcd（need to assemble by youself）x1

DVD x1
Note ： case for main board is not included

Update driver（Oct27th）： Thanks to He.sicong ArhiChief and ,They both provide a new open source driverfor the touchscreen,you can download here ：https://github.com/derekhe/waveshare-7inch-touchscreen 

Or

https://github.com/ArhiChief/eleduino_ts 