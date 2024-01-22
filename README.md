# _VexDebugBoard PCB_

This is the main hardware repository for the V5 Debug Board: a board designed to slot into the VEX V5 Smart Port, 
and transmit debug data over a websocket to a laptop. The data is received by a [Foxglove application](https://foxglove.dev) instance or ROS RViz, and allows for:

- 3D visualization of Odometry
- Real-time graphing for robot tuning
- Wireless print statements

This repository contains the circuit diagram, BOM and PCB layout for the board. 

## Pinout
Smart Port RX (from Brain): GPIO7  
Smart Port TX (to Brain): GPIO6  
RS485 Mode (TX=ON, RX=OFF): GPIO10  
STAT LED: GPIO4  
DBG_LED: GPIO18  
SD SPI MISO: GPIO0  
SD SPI MOSI: GPIO1  
SD SPI CS: GPIO3  
SD SPI SCL: GPIO19  

## Image Library
![Rev3 0_render_top](https://github.com/superrm11/VexDebugBoard_PCB/assets/12285261/89f3f142-e9b1-43fc-b685-5e626f9095aa)
![Rev3 0_render_bottom](https://github.com/superrm11/VexDebugBoard_PCB/assets/12285261/a428013d-a5e3-41c3-b5f3-3f5bb5e20226)
![rev3 0_schematic](https://github.com/superrm11/VexDebugBoard_PCB/assets/12285261/63b4ead1-ed8b-445c-8057-0ad78b61f5e0)
![rev3 0_layout](https://github.com/superrm11/VexDebugBoard_PCB/assets/12285261/cc9551c4-a2aa-43cc-b85f-fc9e14f07688)
