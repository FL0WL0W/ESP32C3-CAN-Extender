# ESP32C3CAN-Module

This module uses an ESP32C3 with WiFi and BLE. 
It has 3 configurable outputs (5V push pull, Open Drain, 12V pullup), 4 analog or digital inputs, CAN transceiver, 
and an automotive power supply so it can be installed directly into a vehicle. It can be programmed and debugged using the edge connector that connects to any standard 
USBC cable. If you decide to order a PCB yourself, make sure to order it as 0.6mm thickness so that the PCB will fit in the USBC connector.
<br/><br/>
The purpose of this module will be to add cruise control, AC control, tachometer output, speedometer output, and fuel consumption output to my LS3 swapped BMW E30.
The LS3 is currently controlled by the stock GM E38 PCM. This PCM (Powertrain Control Module) uses the CAN bus for the aforementioned items, and this is meant to be a bridge from CAN, to 
discrete signals. This job is originally handled by the BCM (Body Control Module), However the BCM includes alot of items that are not needed for a typical swap, and there 
is not very good documentation on the various BCMs available in cars (compatibility, pinout, etc.). In the future, this car will run on an 
<a href="https://github.com/FL0WL0W/EFIGenie">EFIGenie</a> PCM once the software is more mature. This module will then be useful as a CAN extension module.
<br/><br/>
A demo program will be added soon that has all of the aforementioned features hardcoded, but the eventual goal is to utilize the work from my other repositories 
to create a configurable module that can be programmed through a web UI for various tasks.
<br/><br/>
A 3d model of the enclosure will be uploaded soon as well. The plan is to epoxy pot the pcb inside the enclosure to make it waterproof.
![image](https://user-images.githubusercontent.com/1595263/195181301-0c196c3c-3100-4f83-9f30-874a0b7afea7.png)
![image](https://user-images.githubusercontent.com/1595263/195181366-2fab4dbd-18c6-49c6-973a-4e5459182522.png)
![image](https://user-images.githubusercontent.com/1595263/195181392-971070fb-d9a4-4608-bcab-5475aad36f4f.png)
