# ESP-super-sensor-logger
## jam it on. Optimized for a lomng while. Works.

### TLDR: It has the same functionality as Aranet 4 but is better in every way except for the power draw (5w avg).

## Inputs:
```
I2C - SCD-40 CO2 Sensor (also output useless Temp Humi)
I2C - SHT40 Temp Humi Sensor (used for outdoor)
I2C - AHT and BMP on single breakout board Temp Humi Pressure Sensor (used for indoor)
I2C ADC - Light sensor
I2C ADC - Flammable Gas
I2C ADC - Ammonia
I2C ADC - Alcohol
Internal ADC Pin - Motion Radar Sensor
Internal ADC Pin - Battery Voltage
UART - 24Ghz tracking radar module
Wifi - Ping information
(to be implemented: Thingspeak pull, Lora pull, satisfying button)
```
## Outputs:
```
SPI - 1.8' 128*160 RGB TFT
Wifi - Thingspeak 2 channels with all relevant data
UART - Lora Meshtastic device TextMsg
GPIO - Heated sensor heater control (currently not used because no low power mode implemented. Useful to even out inrush current)
I2C - SHT40 high humidity internal heater control
```
## Full version
![IMG20250123214232](https://github.com/user-attachments/assets/63ddce5b-fdc2-4448-b28c-1445d5279e69)
## Base version (keep as many functions as you need)
![IMG_20240106_030131](https://github.com/user-attachments/assets/f22f863a-58d5-4c2a-b65b-897ea5b9fbe5)
## Thinkspeak (what it looks like online - you do not need a lcd screen)
![image](https://github.com/user-attachments/assets/b335641a-826d-4358-9fc0-2c472b284a96)
