# RedLight

## Story

![Schematic View rev1](https://github.com/chuy4ever/RedLight/blob/main/ebike.gif?raw=true)

I ride around Atlanta on the electric mini bike pictured above. However, there is no lighting in the rear. Which according to car drivers can be hard to see at night. Rather than buy a cheap read light from Amazon. I decided to make a overpowered blinking read light to make sure everyone knows I exist. I don't want to be hit by another car.

## Explanation

Uses a 555 timer and a n-channel mosfet to turn on/off LEDs.

The 555 timer is set to a 1-1.5 Hz signal astable square wave providing a steady rear LED.

The input voltage is 12v

rev# marks an existing PCB that has been ordered and purchased. After a rev# is submitted and purchased that revision will not be edited anymore and the next revision will be started. The current revision is rev1

#### Important links for design

LEDs
https://www.mouser.com/ProductDetail/941-XPEBRDL1R250601

LED datasheet
https://www.mouser.com/datasheet/2/723/XLampXPE2-2327163.pdf

LED Eye Safety
https://cree-led.com/media/documents/XLamp_EyeSafety.pdf

LED PCB Thermals
https://cree-led.com/media/documents/XLamp_PCB_Thermal.pdf

## Schematic and Board layout

Schematic view
![Schematic View rev1](https://github.com/chuy4ever/RedLight/blob/main/overpoweredRedLightSchematic.png?raw=true)

Layout view
![Layout View rev1](https://github.com/chuy4ever/RedLight/blob/main/overpoweredRedLightBoard.png?raw=true)

Board view
![Board View rev1](https://github.com/ArmaanLala/LED_Keychain/blob/master/Images/LED_Keychain.png?raw=true)
