# min34

A minimal split keyboard with 34 keys

![pcb](https://github.com/donus3/min34/blob/main/images/pcb.png)


## Features
 - 34 keys (inspired by Sweep)
 - Support a hotswap switch both MX and Kailh low profile style (inspired by SofleKeyboard)
 - Using seeed studio XIAO series microcontroller which means both wire and wireless are available
 - Support a battery switch on/off if Bluetooth microcontroller is used
 - The PCB is reversible
 - No reset button (it's already on the microcontroller)

I don't focus on adding more features like an OLED display or a rotary encoder because I would like to keep it as simple as possible and I personally
don't use them in my daily life (as a programmer).

## Compnents
 - 2x PCBs (for left and right)
 - 2x seeed studio XIAO compatible boards.
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
 - Seeed xiao nrf52840 mcu: https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html
 - Seeed Fusion PCBA service: https://www.seeedstudio.com/pcb-assembly.html
 - Seeed Fusion DIY Mechanical Keyboard contest: https://www.seeedstudio.com/seeed-fusion-diy-xiao-mechanical-keyboard-contest.html

## Gallery

<img src="https://github.com/donus3/min34/blob/main/images/wire-prototype.jpg?raw=true" width="600px" alt="min34-wire" />

<img src="https://github.com/donus3/min34/blob/main/images/no-wire-prototype.jpg?raw=true" width="600px" alt="min34-no-wire" />

<img src="https://github.com/donus3/min34/blob/main/images/back.jpg?raw=true" width="600px" alt="min34-back" />
