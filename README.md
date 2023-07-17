# EASTRON SDM72DM-V2 ESPHome config
Retrieve values from EASTRON SDM72DM-V2 energy meter via RS485 (Modbus) using ESPHome  
and send the values periodically to Home Assistant. 

## Hardware
1x OLIMEX ESP32-POE (or OLIMEX ESP32-POE-ISO) or similar  
1x TTL / UART to RS485 Converter (e.g.: XY-017 or similar)  
1x EASTRON SDM72DM-V2 or similar  

## Remarks
- The smart meter provides many more values. Please refer to the official documentation.  
- Other EASTRON devices can be interfaced in the same way  
- Other ESP32 boards can be used as well.
- The TTL / UART to RS485 board is sold under many different names. The board should not cost more than 2€.  
