# Keyboard MCU List

This is a list of RP2040-based MCUs that can be used in keyboard projects. Much of this data comes
from [Keyboard Builders’ Digest](https://kbd.news) as well as
[r/MechanicalKeyboards](https://www.reddit.com/r/MechanicalKeyboards/).

## RP2040 Pro Micro-Shaped MCUs

| Name                 | Open        | Vendor                 | Colour  | Cast.| Flash | Extra GPIO                         | USB Port | USB Brk. Out | Power LED         | User LED | 1-Btn. Boot |  Buttons  | VBus Det.| Price | Ship.| Total |
|----------------------|:-----------:|------------------------|:-------:|:----:|:-----:|------------------------------------|:--------:|:------------:|:-----------------:|:--------:|:-----------:|:---------:|:--------:|------:|-----:|------:|
| **0xB2 - splinky**   | [Yes][Ob2]  | [Bastard Keyboards][ba]|  Black  | No   | ≤16MB | 5 (bottom)                         |   Mid    |    No        | No                |   Yes    |     No      | 2 (front) |  GPIO19  | (€24) |    ? |     ? |
| **0xCB-Helios**      | [Yes][Ocb]  | [KeebSupply][ks]       |  Black  | Yes  |  16MB | 5 (bottom), 2 (top), 1 (inset, 5V) |   Mid    |    Inset     | Red (optional)    |   Blue   |     Yes     | 1 (front) |  GPIO19  |   €16 |   EU |     ? |
|                      |             | [Keycapsss][kc]        |         |      |       |                                    |          |              |                   |          |             |           |          |   €16 |   €9 |   €25 |
|                      |             | [Ringer Keys][rk]      |         |      |       |                                    |          |              |                   |          |             |           |          |   $20 |   $5 |   $25 |
|                      |             | [RNDKBD][rn]           |         |      |       |                                    |          |              |                   |          |             |           |          |   $18 |   $6 |   $24 |
| **Bit-C PRO**        | No          | [nullbits][nb]         |Black, White|No |   4MB | 4 (bottom)                         |   Top    |    No        | Uses user LEDs    | 3 — RG&B |     Yes     | 0         |  No      |   $20 |   $0 |   $20 |
| **Blok**             | No          | [Boardsource][bs]      |  Black  | Yes  |  16MB | 0, see also note (1) below         |   Mid    |    No        | Purple            |   RGB    |     No      | 2 (side)  |  No      |   $14 |   $5 |   $19 |
| **Elite-Pi**         | No          | [1upkeyboards][1u]     |  Blue   | Yes  |   2MB | 5 (bottom), 2 (pads)               |   Mid    |    Pads      | No                |   No     |     No      | 2 (front) |  No      |   $17 |   $0 |   $17 |
|                      |             | [Keebio][io]           |         |      |       |                                    |          |              |                   |          |             |           |          |   $13 |   $5 |   $18 |
| **Frood RP2040**     | [Yes][Ofr]  | [42.Keebs][42]         | Various | No   |   4MB | 5                                  |   Mid    |    Top       | No                |  Orange  |     No      | 2 (front) |  GPIO19  |   €11 |   €5 |   €16 |
| **KB2040 Kee Boar**  | No          | [Adafruit][af]         |  Black  | Yes  |   8MB | 2 (Qwiic), see also note (2) below |   Top    |    Top       | Green             |   RGB    |     No      | 2 (front) |  No      |    $9 |   $4 |   $13 |
| **key micro RP**     | No          | [BOOTH][bo]            |  Black  | No   |   4MB | 0                                  |   Mid    |    Pads      | No                |   No     |     No      | 2 (side)  |  No      | ¥2700 |    ? |     ? |
| **Laitris**          | No          | [splitkb][sk]          |  Black  | Yes  |  16MB | 5 (row, 5V)                        |   Mid    |    Pads      | Yes (back, GPIO24)|   RGB    |     No      | 1 (back)  |  No      |   €15 |  €18 |   €33 |
| **Pro Micro RP2040** | [Yes][Opm]  | [SparkFun][sf]         |   Red   | Yes  |  16MB | 2 (Qwiic)                          |   Top    |    Pads      | Red               |   RGB    |     No      | 2 (front) |  No      |   $11 |  $11 |   $22 |
| **RP2040 Pro Micro** | No          | [Tenstar Robot][tr]³   |  Black  | No   | 4/16MB| 5 (bottom), 3 (inset)              |   Mid    |    No        | No                |   RGB    |     No      | 2 (front) |  No      |    $3 |   $2 |    $5 |
| **Sea-Picro EXT**    | [Yes][Osp]  | [beekeeb][bk]          |  Black  | No   |  16MB | 5 (bottom), 1 (inset, 5V)          |   Mid    |    Top       | No                |   No     |     Yes     | 0         |  GPIO19  |   $10 |   $8 |   $18 |
|                      |             | [Custom KBD][ck]       |  Black  | Yes  |       |                                    |          |              |                   |          |             |           |          |   $17 |  $15 |   $32 |
| **Sea-Picro RST**    | [Yes][Osp]  | None                   |  Black  | No   |  16MB | 0                                  |   Mid    |    Top       | No                |   RGB    |     Yes     | 1 (front) |  GPIO19  |       |      |       |
| **svlinky**          | [Yes][Osv]  | [fingerpunch][fp]      |  Black  | No   |   8MB | 9 (VIK)                            |   Mid    |    No        | No                |   Yes    |     No      | 0         |  GPIO19  |   $15 |  $10 |   $25 |

[Ob2]: https://github.com/plut0nium/0xB2
[Ocb]: https://github.com/0xCB-dev/0xCB-Helios
[Ofr]: https://github.com/piit79/Frood
[Opm]: https://github.com/sparkfun/SparkFun_Pro_Micro-RP2040
[Osp]: https://github.com/joshajohnson/sea-picro
[Osv]: https://github.com/sadekbaroudi/svlinky

[1u]: https://1upkeyboards.com/shop/controllers/elite-pi-controller/
[42]: https://42keebs.eu/shop/parts/controllers/frood-rp2040-pro-micro-controller/
[af]: https://www.adafruit.com/product/5302
[ba]: https://bastardkb.com/product/splinky-rp2040-controller/
[bk]: https://shop.beekeeb.com/product/sea-picro/
[bo]: https://booth.pm/ja/items/3703539
[bs]: https://www.boardsource.xyz/store/628b95b494dfa308a6581622
[ck]: https://customkbd.com/collections/microcontrollers/products/sea-picro
[fp]: https://fingerpunch.xyz/product/svlinky/
[io]: https://keeb.io/products/elite-pi-usb-c-pro-micro-replacement-rp2040
[kc]: https://keycapsss.com/keyboard-parts/mcu-controller/257/0xcb-helios-pro-micro/elite-c-compatible-microcontroller-with-rp2040?c=22
[ks]: https://keeb.supply/products/0xcb-helios
[nb]: https://nullbits.co/bit-c-pro/
[rk]: https://ringerkeys.com/collections/modders-tools/products/0xcb-helios
[rn]: https://rndkbd.com/products/0xcb-helios-microcontroller
[sf]: https://www.sparkfun.com/products/18288
[sk]: https://splitkb.com/products/liatris
[tr]: https://www.aliexpress.com/item/3256805943704472.html

### Notes on Columns

 * Open — indicates whether the schematic and/or PCB design is openly documented (if not actually
   released under an open source license), and links to that documentation if available.
 * Cast. — indicates whether the PCB is castellated or not.
 * Extra GPIO — indicates the number and location of any I/O pins beyond the [usual 18 for a
   Pro Micro](https://cdn.sparkfun.com/assets/9/c/3/c/4/523a1765757b7f5c6e8b4567.png):
    * Bottom — located on the “bottom” row of the PCB (if the USB port is the “top”)
    * Top — located on either side of the USB port above the usual Pro Micro pins
    * Inset — located inside the usual pins
    * Pads — I/O is accessed via solder pads on the reverse of the PCB rather than through-hole
      connections
    * [Qwiic] — SparkFun’s I²C interconnect system that uses a four-pin JST connector to provide
      3.3V, GND and two I/O
    * [VIK] — an interconnect system that uses a twelve-pin FPC connector to provide 5V, 3.3V, GND
      and 9 I/O
    * 5V — indicates that the output signal is at 5V rather that 3.3V, which means that RGB LEDs can
      be driven at spec
 * USB Port — all boards are USB C unless noted, a mid-mount board will typically result in an
   overall MCU thickness of 3.2mm (the thickness of a USB C port), while a top-mount board will be
   3.2mm plus the thickness of the PCB (typically 1.6mm).
 * USB Brk. Out — indicates whether there is access to the USB data (i.e., whether a USB breakout
   board be used with this MCU), and the type and approximate location of the access points.
   Locations are as Extra GPIO pins above.
 * User LED — indicates whether there is an onboard LED (single colour or RGB) that can be accessed
   from firmware.
 * 1-Btn. Boot — indicates whether the board has a combined reset and boot circuit (e.g., a short
   press will reset, while a long press will reboot). This means that only one on-board reset/boot
   button is required and off-MCU reset buttons can be used to go into boot-loader mode (once
   installed and appropriately configured, QMK can also trigger this via [a double-tap of the reset
   button](https://docs.qmk.fm/#/platformdev_rp2040?id=double-tap)).
 * Buttons — indicates whether there are onboard reset/boot buttons and their general location:
    * Front — the side of the board with most components and the USB port (if top mounted)
    * Back — the other, usually unpopulated, side of the board
    * Side — facing sideways from the board in the opposite direction to the USB port
 * VBus Det. — indicates whether the board has a built-in VBUS detection circuit.
 * Price — price of a single MCU before tax as of March 2024 in US dollars, euros or yen. To be used
   as a very rough guide to comparative cost.
 * Ship. — lowest available cost as of March 2024 in US dollars or euros of shipping one MCU to
   the continental US (if possible). Populated with an appropriate country/region code if shipping
   area is limited.
 * Total — Price plus Shipping. Again, to be used as a very rough guide to comparative cost for a
   single MCU. Does not include cost savings for multiple units, etc.

[Qwiic]: https://www.sparkfun.com/qwiic
[VIK]: https://github.com/sadekbaroudi/vik

### Notes on Rows

 1. Blok has [GPIO 16 and 17](https://peg.software/docs/blok) instead of 2 and 3 respectively.
 2. KB2040 has [GPIO 10, 18 and 19](https://learn.adafruit.com/adafruit-kb2040/pinouts) instead of
    21, 22 and 23 respectively.
 3. The unbranded “RP2040 Pro Micro” is available at [various AliExpress
    stores](https://www.aliexpress.com/w/wholesale-RP2040-Pro-Micro.html).



## Other RP2040 MCUs

A small selection of RP2040-based MCUs that are *not* shaped like a Pro Micro.

| Name              | Open        | Vendor             | Size (mm) | Colour | Cast.| Flash | Total GPIO   |  USB Port  | USB Brk. Out | Power LED | User LED | 1-Btn. Boot |  Buttons  | VBus Det.| Price | Ship.| Total |
|-------------------|:-----------:|--------------------|:---------:|:------:|:----:|:-----:|--------------|:----------:|:------------:|:---------:|:--------:|:-----------:|:---------:|:--------:|------:|-----:|------:|
| Raspberry Pi Pico | [Yes][Opp]  | [Various][rp]      | 21.0×51.3 | Green  | Yes  |   2MB | 26           | Top, Micro!|     Pads     |    No     |   RGB    |     No      | 1 (front) |  GPIO24  |    $4 |   $4 |    $8 |
| RP2040-Zero       | [Part][Op0] | [WaveShare][ws]    | 18.0×23.5 | Blue   | Yes  |   2MB | 20, 9 (pads) |    Top     |     No       |    No     |   RGB    |     No      | 2 (front) |  No      |    $4 |   $6 |   $10 |
| Seeed XIAO RP2040 | [Part][Osx] | [Seeed Studio][ss] | 17.5×21.0 | Black  | Yes  |   2MB | 11           |    Top     |     No       |    Red    |RGB, 3RG&B|     No      | 2 (front) |  No      |    $5 |   $7 |   $12 |
| Stampy            | No          | [Keebio][ke]       | 57.3×21.5 | Purple | No   |   2MB | 26           |    Top     |     No       |    No     |   No     |     No      | 1 (front) |  GPIO9   |   $13 |   $6 |   $19 |

[Opp]: https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html#raspberry-pi-pico
[Op0]: https://files.waveshare.com/upload/4/4c/RP2040_Zero.pdf
[Osx]: https://files.seeedstudio.com/wiki/XIAO-RP2040/res/Seeed-Studio-XIAO-RP2040-v1.3.pdf

[ws]: https://www.waveshare.com/rp2040-zero.htm
[rp]: https://www.raspberrypi.com/products/raspberry-pi-pico/#find-reseller
[ss]: https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html
[ke]: https://keeb.io/products/stampy-rp2040-usb-c-controller-board-for-handwiring
