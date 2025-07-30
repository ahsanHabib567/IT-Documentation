## Place:
**JSSL Services LTD - Dhaka**
## Issue: 
**Network loop issue - Wifi works well, but the cable-connected device's network behaves abnormally. Link gets up/down in a short time.**
## Reason:  
**There was a fault in the switches that caused the problem. All the end devices are connected via cable to the switches. There is also a gateway device for the VoIP phones. That gateway is connected to a switch on port 3. The port is damaged. Maybe this was causing the loop issue.**
## Approach:  
**1. Restarted the network stack. Plugged in and out all the important Ethernet cables.**  
**2. Changed the VoIP phone gateway device to port 5 of the switch. [Solved]**

