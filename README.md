Description:
Those are adapter boards that will allow you to use the HS402 oscilloscope wirelessly via an ESP32 (WROOM32 or WROOM32D).
The adapter board was designed to allow a 30 pin (Version_1) or 38 pin (Version_2) NodeMCU (WROOM32 or WROOM32D) to be stacked on top of an STM32F411.
 
!!! Before ordering this PCB adapter, ensure that your ESP32 NodeMCU board pinout (30 pin) is exactly as the one shown in the picture [NODEMCU-ESP32-30pins.png]!!!
!!! Before ordering this PCB adapter, ensure that your ESP32 NodeMCU board pinout (38 pin) is exactly as the one shown in the picture [NODEMCU-ESP32-38pins.png]!!!
 
Steps for the assembling:
1. Solder the male headers on the STM32F411,
2. Remove the plastic spacers from the male headers,
3. Place the STM32F411 on the adapter board, and solder the relevant pins to the adapter board (GND, VCC, PB12, PB13, PB14, PA9, and PA10).
4. Fit the adapter into the HS402 oscilloscope mainboard and test that everything works as expected,
5. Solder some of the remaining STM32F411 pins to ensure mechanical strength - choose pins from both sides of the STM32F411,
6. Solder the male headers on the ESP32 NodeMCU - some may skip this, as headers may have been are already soldered,
7. Solder the female headers on the adapter board,
8. Fit the ESP32 on the adapter board,
9. Solder the wires to provide power supply to the 2 boards,
10. Provide 5 volts to the soldered wires, taking care of the voltage polarity,
11. Enjoy your new wireless oscilloscope.
 
Notes:
Those adapter boards are not the official WiFi adapters for HS402 oscilloscope.
So this design is not maintained or suported by the developer of HS402 oscilloscope. 
This adapter is a reduced version with fewer functions (no voltage monitoring and for Version 1 no RGB LED indications).

Order it only after you understand his limitations.
 
For more Infos about how to build the HS402 oscilloscope and how to prepare the boards for WiFi operation, please check the HS402 oscilloscope webpage.
