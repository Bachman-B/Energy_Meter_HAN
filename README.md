ESP32 Swedish Smart meter (DSMR) parser - HAN Protocol
======================================================
This is an ESP32 /Home Assistant library for interfacing withSwedish HAN meters, through
their P1 port. This library can take care of controlling the "request" pin,
reading messages and parsing them.

This code was been taken from [Matthijs Kooijman](https://github.com/matthijskooijman/arduino-dsmr)
and been modified to match HAN protocol [HANporten.se](https://hanporten.se/)



## Schematics
![Schema](https://github.com/Bachman-B/Energy_Meter_HAN/blob/main/Images/EM.JPG?raw=true)

##BOM
| Part     | Value         |
| -------- | -------------:|
| C1       | 1000uF        |
| C2       |  100nF        |
| IC1      | ESP32CAM      |
| IC2      | 74LS04        |
| R1         | 1k            |
| R2         | 1k            |
| R3         | 1k            |
| R4         | 1k            |
| U$1      | Soldering from RJ12              |

                                                                                                                                                                                                                                                                                                                                                   



## Attribution & Thanks
1. [Matthijs Kooijman](https://github.com/matthijskooijman/arduino-dsmr)
2. [nldroid](https://github.com/nldroid/CustomP1UartComponent)
3. [ESP32 Pinout Reference](https://lastminuteengineers.com/esp32-pinout-reference/)

## License
All of the code and documentation in this library is licensed under the MIT license
