# LED Puzzle

## Description:
This project goes through step by step build guide on how to create a LED backed
puzzle frame. The puzzle is made of transparent plastic that can have light shown
through. The premise of this project is to utilize this property of the puzzle
and control the color and amount of light shown through the puzzle with LEDs. The 
LEDs will have several presets and controlled by an IR remote. 

## Components

### Raspberry Pi Pico W
The microcontroller that will control the LEDs and receive commands to change the
LED states from the IR remote. The Pico W will be controlled with [MicroPython](https://micropython.org/)
as it is the easier to get started and developed quickly. There is no specific need
to optimize the speed of the controller as it is only setting the state of the LEDs. 
Code for the controller could later be developed in C if need arises.

### WS2812 RGB LEDs https://www.aliexpress.us/item/2251801850504415.html?spm=a2g0o.order_list.order_list_main.17.21ef1802FIAkct&gatewayAdapt=glo2usa&_randl_shipto=US
These LEDs are commonly found on LED light strips. They are good options for this project
because they provide a low profile means to mount LEDs onto a back plate to keep the 
overall frame thin. An alternative would be the neolight strips. These strips come pre-soldered
with diodes and the individual LEDs and can easily be cut into individual units needed
for this project.

### Frosted Acrylic or glass
Frosted transparent mediums allow for the diffusion of light from the LEDs. It would not be 
visually appealling to show individual cells of LEDs behind the puzzle. Therefore, this mediums
aids in blending the light prior to illuminating the puzzle

### Wire

### Solder

### Lithium Battery Charger Module

### Lithium Polymer Battery
https://www.amazon.com/KBT-3-7V-9500mAh-Li-Polymer-Battery/dp/B0BJPS6889/ref=sr_1_21_sspa?crid=3J9I1DXO7HVUG&keywords=lipo%2Bbattery&qid=1682829668&sprefix=lipo%2Bbattery%2Caps%2C92&sr=8-21-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyOVlKR1hRTDA2VjlCJmVuY3J5cHRlZElkPUEwMDU4MDEwMUVUWkdWN1ZTNkpaWiZlbmNyeXB0ZWRBZElkPUEwNzA4OTk2Mk1KWUk0SlJSOTRDWSZ3aWRnZXROYW1lPXNwX210ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU&th=1

### 1/4 inch Plywood

### IR Receiver and IR remote

### Voltage Step up


## Resources
### NeoPixel Example Code
https://github.com/Guitarman9119/Raspberry-Pi-Pico-/tree/main/Neopixel

### IR
https://github.com/owainm713/IR-Remote-Receiver-Python-Module
