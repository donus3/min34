# min34

A minimal split keyboard with 34 keys

![pcb](https://github.com/donus3/min34/blob/main/images/pcb.png)


## Features
 - 34 keys (inspired by Sweep)
 - Support a hotswap switch both MX and Kailh low profile style (inspired by SofleKeyboard)
 - Using seeeduino XIAO series microcontroller which means both wire and wireless are available
 - Support a battery switch on/off if Bluetooth microcontroller is used
 - The PCB is reversible
 - No reset button (it's already on the microcontroller)

I am not not focus on adding more features like an OLED display or a rotary encoder because I would like to keep it as simple as possible and I personally
use them in my daily life (as a programmer).

## Compnents
 - 2x PCBs (for left and right)
 - 2x seeeduino XIAO compatible boards.
 - 34 switches of MX or Kailh low profile style
 - 34 kailh switch sockets (MX or Kailh low profile)
 - 34 diodes 1N4148W
 - 34 keycaps
 - (optional; only for battery support) 2x power switches (MSK 12C02)
 - (optional; only for wire support) 2x TRRS connectors
 - (optional; only for wire support) 1x TRRS cable
 - 1 USB Cable

## Firmware
Please refer to [min34 zmk config](./firmware)

## Thanks to
 - [SofleKeyboard](https://github.com/josefadamcik/SofleKeyboard)
 - [crkbd](https://github.com/foostan/crkbd)
 - [Slice36](https://github.com/MReavley/Slice36)
 - [Sweep](https://github.com/davidphilipbarr/Sweep)

## Gallery

![wireless](https://github.com/donus3/min34/blob/main/images/wireless.jpg?raw=true)
![wire](https://github.com/donus3/min34/blob/main/images/wire.jpg?raw=true)
![back](https://github.com/donus3/min34/blob/main/images/back.jpg?raw=true)