# White LED clock with Arduino Nano ESP32, shift registers and Darlington array

A white LED word clock with Arduino ano ESP32 controlled with shift registers.
![V01-ESP32-HC595-3D](https://github.com/user-attachments/assets/c93c6547-6e5b-41f7-8211-471cd1d284f9)

This small PCB is used to built a Word clock with white LED strips and an LDR to control the light intensity of the LED-strip.
The PCB is also handy for design purposes with an Arduino Nano ESP32 and can be used to turn on and off up to 32 LED-strips or other devices that draws power up to 500mA and up to 50V.

This PCB design were kindly supported by [PCBWay](https://www.pcbway.com) that made the development of this PCB possible.<br>
The PCB was designed with Fritzing and the Gerber files uploaded to  the PCBWay web site.<br>
Just upload the [Gerber files from the ZIP file][(https://github.com/ednieuw/NanoESP32PCB)](https://github.com/ednieuw/ESP32ShiftregisterBWclock/blob/main/HC595ESP32V01.ZIP) to their site and pay the charges. Piece of cake.<br>
The PCB's looked perfect and soldering the components was easy.

This PCB is a part of the [Ultimate word clock PCB](https://github.com/ednieuw/NanoESP32-BW-RGBW-clock).<br>
The software from this clock will be modified for this PCB in due time but you can do it your self in the mean time.

The only sensor is the LDR sensor and the transistors to generate a pulse width modulation (PWM) pulse to control the intensity of the LED-strips.<br>
With the WIFI and Bluetooth connection the clock can be controlled and get its time via NTP over WIFI.


