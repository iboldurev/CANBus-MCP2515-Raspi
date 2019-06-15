# MCP2515 CANBus module installation on RaspberryPi  
It is aimed to build CANBus communication between two Raspberry Pi boards. This setup is accomplished with the Microchip's stand-alone MCP2515 CAN controller. 

## Project Items  
> 1 RaspberryPi 3 Model B+ (Raspi1)   
> 1 RaspberryPi 3 Model B v1.2 (Raspi2)   
> 2 MCP2515 CAN Bus Module TJA1050 Receiver SPI (CanModule1, CanModule2)    
> Environmental Setup     

## High Level Design 
Raspi1 --(SPIcomm)-- CanModule1 ==<CANbus H,L>== CanModule2 --(SPIComm)-- Raspi2
![Test Image 1](https://github.com/tolgakarakurt/CANBus-MCP2515-Raspi/blob/master/CANBus-2MCP2515-Page-1.png)

## Wiring Diagrams
**MCP2515**
![Test Image 2](https://github.com/tolgakarakurt/CANBus-MCP2515-Raspi/blob/master/CANBus-2MCP2515.png)
## Installation
>>ss
>>f

    
  
  

## Learn More  
**RaspberryPi 3 Model B+**     
> https://en.wikipedia.org/wiki/Raspberry_Pi    
> https://pinout.xyz/  

**MCP2515 Can Controller** 
> https://www.microchip.com/wwwproducts/en/en010406  
> http://ww1.microchip.com/downloads/en/DeviceDoc/MCP2515-Stand-Alone-CAN-Controller-with-SPI-20001801J.pdf  
> https://www.nxp.com/docs/en/data-sheet/TJA1050.pdf  

