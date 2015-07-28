# STM32-Sunrise

Based on the Project I started on Hackaday quite some time ago. 

https://hackaday.io/project/2126-sunset-and-sunrise-camera-controller

The original code ran on a Maple Mini with a RTC module. 

This version is designed to be entirely STM32F103 based, with a relay or MOSFET to switch the camera battery. 

The code in the repo will run on pretty much any STM32F103X board, but I'm working with an STM32F103RX series board similar to this. 

http://www.ebay.co.uk/itm/261946671718?_trksid=p2057872.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT

See http://www.stm32duino.com/index.php for details regarding using the Arduino IDE with the low cost STM32 series boards. 

The code could no doubt still be made to work with a standard Arduino AVR based board with an add on RTC module, but as it stands, it uses the on board RTC of the STM32F103

