# Tag-Connect TC2030 to Atmel ICE Adapter

There is a Tag-Connect cable that will go directly into the fine-pitch 10-pin IDC connector on the Atmel ICE, but the cable is expensive and I felt like spending $60 on a cable that could only be used with that device would be silly. To add to the confusion, Tag-Connect sells "LEMTA" cables, which have a different pinout to match that of the Atmel ICE. 

The cable I bought is the Tag-Connect TC2030, which has a standard .1" pitch 6-pin connector, and is *not* the LEMTA version. With that cable, I can connect it to any random ISP programmer, but when it came to the Atmel ICE, I needed a way to connect the two together. That's how this adapter PCB came about. Having this PCB and the TC2030 cable is a good way to make use of the Tag-Connect system, I think. If you want one, you can submit the .zip file to OSHpark, JLCPCB, or whomever you like and solder a couple of 2x6 male headers onto the PCB.

BTW, The Eagle files are also provided, if you want to change the silk screen (which says "AVR-ICE" instead of "ATMEL-ICE"), panelize the board, or whatever.

![image](https://github.com/rahji/tc2030_ice/assets/442495/178ef190-dc7e-41ca-ae3e-39d5fabdd04b)
