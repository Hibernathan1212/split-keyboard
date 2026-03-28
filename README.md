# SPlitty

An ergonomic ortholinear split keyboard made to be low profile yet enjoyable and comfortable to use. It features a 6 column by 3 row layout similar to the Corne ergo keyboard but instead with a full width bottom "thumb cluster" that hopefully helps in moving from a traditional keyboard to a split ergo thumb cluster. This is mostly based around many of my current workflows being based around using CMD CTRL and ALT together on my mac so I wanted a way to reliably (no mod tap/hold on home row) press all of them while pressing all the other keys. I have an absolem/voyager style sticking out thumb cluster which allows for a more natural open hand. I wanted to make this project to help with the uncomfortable ergonomics of my desk that make me hunch forward to my keyboard whereas I'd rather my arms be further apart.

<img src=assets/cad.png alt="Cad" width="500"/>

## Features

- Ortholinear
- Column staggered
- 48 keys
- Pinky splay
- 128x32 OLED Displays
- Customizable tilt with tent legs
- ZMK Firmware
- Low Profile Choc Linear Switches
- Wireless
- Hotswappable

## CAD

Uses a mix between a floating tray mount (resting on top of pillars) and a floating integrated plate on a lip to get the benefits of rigidity from tray mount without being too rigid and also alignment from plate.

<img src=assets/left-cad.png alt="Left" width="500"/>
<img src=assets/right-cad.png alt="Right" width="500"/>

Made in Onshape.

## PCB

Made in Kicad

### Schematic

<img src=assets/schematic.png alt="schematic" width="500"/>

### PCB

<img src=assets/left-pcb.png alt="pcb" width="500"/>
<img src=assets/right-pcb.png alt="pcb" width="500"/>

## Firmware

Uses ZMK and is customizable to do whatever you want pretty much. Set up to work with ZMK Studio. By default has 4 layers: the default qwerty layout layer, a numpad & function keys layout, a symbols layer, and a nav layer with mouse movements.

## BOM

| Product                             | Amount | Unit Cost (THB) | Price (THB) | Price (USD) | Link                                                                                                                                                                                              |
| ----------------------------------- | ------ | --------------- | ----------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Kailh Choc Low Profile Switches V1  | 70     | 791.58          | 791.58      | 24.09       | [https://th.aliexpress.com/item/1005005723938995.html](https://th.aliexpress.com/item/1005005723938995.html)                                                                                      |
| Kailh Choc Low Profile Keycaps 1u   | 5\*10  | 135             | 675         | 20.54       | [https://keebd.com/products/ldsa-low-profile-blank-keycaps?variant=43210374185112](https://keebd.com/products/ldsa-low-profile-blank-keycaps?variant=43210374185112)                              |
| Kailh Choc Low Profile Keycaps 1.5u | 1\*2   | 51              | 51          | 1.55        | [https://keebd.com/products/ldsa-low-profile-blank-keycaps?variant=43210375397528](https://keebd.com/products/ldsa-low-profile-blank-keycaps?variant=43210375397528)                              |
| Choc Hotswap Sockets                | 50     | 177.03          | 177.03      | 5.39        | [https://th.aliexpress.com/item/1005008543325730.html](https://th.aliexpress.com/item/1005008543325730.html)                                                                                      |
| Reset Button                        | 2      | 51              | 102         | 3.1         | [https://keebd.com/products/reset-button-panasonic](https://keebd.com/products/reset-button-panasonic?srsltid=AfmBOoqrNr1D5JySXj1dNxAi4vIIM-d_Cx6PHS7UyMUKO7owCQmBtrpF)                           |
| Power Switch                        | 2      | 26              | 52          | 1.58        | [https://keebd.com/products/switch-mini-7-pin-2-slide-positions](https://keebd.com/products/switch-mini-7-pin-2-slide-positions?srsltid=AfmBOooT0UHBg7pBa6EjpS95Rs0mNn8pMlFmb-gIRtZvkFgxmaAJpZwf) |
| Rubber Feet                         | 4      | 73.6            | 73.6        | 2.24        | [https://th.aliexpress.com/item/1005007438396940.html](https://th.aliexpress.com/item/1005007438396940.html)                                                                                      |
| Tenting Feet                        | 4      | 58.83           | 235.32      | 7.16        | [https://th.aliexpress.com/item/1005011724480659.html](https://th.aliexpress.com/item/1005011724480659.html)                                                                                      |
| 403450 750mAh                       | 2      | 130.24          | 260.48      | 7.93        | [https://th.aliexpress.com/item/1005003630012646.html](https://th.aliexpress.com/item/1005003630012646.html)                                                                                      |
| Battery JST PH Connector            | 2      | 51              | 102         | 3.1         | [https://keebd.com/products/jst-power-connector](https://keebd.com/products/jst-power-connector?srsltid=AfmBOopmdEJXwQjZOcXiPiyuZl3NNfB-quLRRi4P3NJ0IHfXKXBFPR9Q)                                 |
| ProMicro nrf52840 Board             | 2      | 106.15          | 212.3       | 6.46        | [https://th.aliexpress.com/item/1005006271779544.html](https://th.aliexpress.com/item/1005006271779544.html)                                                                                      |
| Diodes                              | 1      | 25.78           | 25.78       | 0.78        | [https://th.aliexpress.com/item/1005008826378208.html](https://th.aliexpress.com/item/1005008826378208.html)                                                                                      |
| Oled Display 0.91inch I2C           | 1      | 155.34          | 155.34      | 4.73        | [https://th.aliexpress.com/item/1005008918700196.html](https://th.aliexpress.com/item/1005008918700196.html)                                                                                      |
| PCB left                            | 1      |                 |             | 10          |                                                                                                                                                                                                   |
| PCB right                           | 1      |                 |             | 10          |                                                                                                                                                                                                   |
|                                     |        |                 |             |             |                                                                                                                                                                                                   |
| aliexpress shipping                 |        |                 | 143.8       | 4.38        |                                                                                                                                                                                                   |
| keebd shipping                      |        |                 | 230         | 7           |                                                                                                                                                                                                   |
| jlcpcb shipping                     |        |                 |             | 0.05        |                                                                                                                                                                                                   |
|                                     |        |                 |             |             |                                                                                                                                                                                                   |
| Total                               |        |                 |             | 120.08      |                                                                                                                                                                                                   |

(If anyone could help source cheaper materials it would be greatly appreciated)
