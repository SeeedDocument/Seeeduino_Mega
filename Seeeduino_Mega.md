#Seeeduino Mega
------

##Introduction

![](https://github.com/SeeedDocument/Seeeduino_Mega/blob/master/images/Seeeduino_Mega_cover.jpg?raw=true

Seeeduino Mega is a powerful microcontroller derived from Arduino Mega. It features ATmega2560 processor which brings a large number of I/O pins, as much as 70 digital I/O, 16 analog inputs, 14 PWM, and 4 hardware serial ports. Compared to Arduino Mega, we shrunk the volume of Arduino Mega by at least 30% and made it 100% compatible with [Seeed Shield products](https://www.seeedstudio.com/s/shield.html). And as a member of Seeeduino series, Seeeduino Mega inherits deliberate details from Seeeduino, like selectable operating voltage(3.3V/5V), right angle reset button, and so on.

[![](https://github.com/SeeedDocument/BeagleBone_Green_Wireless/blob/master/images/get_one_now.png?raw=true)](https://www.seeedstudio.com/Seeeduino-Mega-p-717.html)


##Application Ideas

* Internet of Things  
* Smart House
* 3D Printer
* Industrial

Here is some funny project for your reference.


##Features

* Compatible with most Arduino Duemilanove and Diecimila Shields
* ATmega 2560 @ 16MHz
* Selectable 5V/3.3V operation
* 70 Digital IO
* 16 Analog inputs
* 14 PWM outputs
* 4 Hardware serial ports (UART)
* Small form factor, 30% smaller than Arduino Mega
* Easy to program, no additional hardware is required to load firmware – just plug to a USB port and you’re good to go.
* ICSP Header
* Can be powered through a battery or through a AC to DC adaptor

##Specification

|Item|Value|
|------------|-----------|
|Microcontroller|ATmega2560|
|Operating Voltage|5V/3.3V|
|Input Voltage|7-12V|
|Digital I/O Pins|70|
|PWM Channels|14|
|Analog Input Channels|16|
|DC Current per I/O Pin|20 mA|
|Flash Memory|256 KB|
|RAM|8 KB|
|EEPROM|4 KB|
|Clock Speed|16 MHz|


##Hardware Overview

The images below show an overview of Seeeduino Mega hardware features. The pin-out and alternate functions of various pins of Seeeduino Mega are shown in the pin-out diagram. This could be used as a quick reference.

![](https://github.com/SeeedDocument/Seeeduino_Mega/blob/master/images/Seeeduino_Mega_hardware1.png?raw=true)

 
- **Mini USB**
Mini USB Port is used to connect the board to your PC for programming and for powering up. 
- **Mode Switch**
Slide switch used to allow or avoid automatic reset and upload.
- **Power Switch**
Slide switch used to change the logic level and power output of the board to either 5V or 3.3V. Nowadays many new and great sensors are being develop to work with 3.3V, with other duino boards you would need to place a logic level converter between the board and these sensor(s), with the Seeeduino Mega all you have to do is slide the switch!
- **DC Input**
The DC Input allows your Seeeduino Mega to be powered from a wall adapter so that you can supply more power to your project if needed, for example when using DC motors or other high power devices. The DC input can be 7V-12V. As peak current is 2A when model is power on, DC Power is your better choice then USB power.
- **Reset**
This button is conveniently placed on the side to allow you to reset the Seeeduino board even when a shield is placed on top. This is not the case in other Arduino boards where the button is placed on top making it hard to access.
- **Digital Pins**

- **ICSP**
This is the ICSP connection for the ATmega328P, it is located in the standard ICSP/SPI position for Arduino Uno, Due, Mega, and Leonardo compatible hardware (e.g. shields) that may use this connector. The SPI pins in this port: MISO, SCK, and MOSI, are also connected to digital pins 12, 13, and 11 respectively just like those of the Arduino Uno.


##Getting Started



##Resources

##FAQ

* What is the different between Arduino Mega

##Help us to make it better