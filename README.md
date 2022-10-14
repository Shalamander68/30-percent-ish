# 30% ish
this keyboard combines the best of ergonomics, portibality and more features then you will ever use. this keyboard is a low profile split keyboard that can be configured on the fly to have a 30% or 40% layout with othr optinal atachments avaliable. it has individuley controled LED back lights, a large battery and bluetooth. best of all its all open source and waiting for you to add you modules and features. it was inspired by the ferris and ferris sweep, with the major changes being control boards and the thumb keys.

## Specs
- 40 key layout
- split with arch wire
- BLE and wired conection
- USB-C
- epansion ports
- ripi picos for extra IO
- custom PCB
- Per key RGB LEDs
- 

## BOM
- 2x pi picos
- seed stuidos Xaio
- 40 choc switches
- 2 TRRS ports
- TRRS male to TRRS male cable
- extra pin headers
- USB C cable (for wired usage)
- LIPO battery
- 40 SK6812 MINI LEDs
- ~20 XT 30 conectors
- 18 gauge wire ( simmilar size wire may work )
**(does not include parts for any expansions)**
most parts can be ordered from digikey, with the fallowing coming from amazon or adafruit

## tools needed
- soldering iron, solder and flux (fine tip recomended)
- 3d printer (resin or fillament will work) (could be sent to a company to print)
- wire stripers and cutters
- eletrical tape
- simple tools like pliers and side cutters will make hte project easyer

## basic control scheme
thanks to the extra IO from the pi pico a matrix is not nesicary simplifying the PCB and reduceing costs. the IO on the pico makes up the main 20 keys per side. with the 6 remaining IO pins support for Track points, track balls, rotary encoders and extra keys is added. this conector is on the top right of the board. there is also unused IO on the Xaio witch is used for 6 more GPIO pins on the left of the keyboard, adding support for the same things as above but also alowing the board to become a 40%. the Xaio and picos are conected with 2ic, larger expantions could be done with I/O expanders reduceing the conector to a 3/4 pin. all keys are conected to ground and one GPIO pin, witch lets us route traces on a single side of the board. the other side of the board is used for the controle components and conectors. a second board seprated by stand offs might be added, but would be pannled with the other PCBs. 

## features
- 5 thumb keys
- switchable 30% and 40% layout
- Bluetooth support
- optinal encoders, extra keys and LCDs
- Per key LED lighting
- easy key remaping
- Low profile and easy to transport
- laptop clips to replace the laptops keyboard with ours
- elemanate the TRRS cable with conectos between the boards
