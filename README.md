# Keyboard MCU List

This is a list of RP2040-based ProMicro-shaped MCUs that can be used in keyboard
projects. Much of this data comes from [Keyboard Builders’ Digest](https://kbd.news) as well as
[r/MechanicalKeyboards](https://www.reddit.com/r/MechanicalKeyboards/).

## RP2040 ProMicro-Shaped MCUs

| Name                 | Open Source | Vendor                 | Colour  | Cast. | Flash | Extra GPIO                             | USB Port |  USB Brk. Out  | Power LED         | User LED | 1-Btn. Boot |   Buttons   | VBus Det. | Price | Shipping | Total |
|----------------------|:-----------:|------------------------|:-------:|:-----:|:-----:|----------------------------------------|:--------:|:--------------:|:-----------------:|:--------:|:-----------:|:-----------:|:---------:|------:|---------:|------:|
| **0xB2 - splinky**   | [Yes][Ob2]  | [Bastard Keyboards][ba]|  Black  |  No   | ≤16MB | 5 (bottom row)                         |   Mid    |       No       | No                |   Yes    |    No       | 2 (front)   |   GPIO19  |   €20 |      N/A |     ? |
| **0xCB-Helios**      | [Yes][Ocb]  | [KeebSupply][ks]       |  Black  |  Yes  |  16MB | 5 (bottom row), 2 (top), 1 (inset, 5V) |   Mid    |  Pins (inset)  | Red (optional)    |   Blue   |    Yes      | 1 (front)   |   GPIO19  |   €16 |  EU only |     ? |
|                      |             | [Keycapsss][kc]        |         |       |       |                                        |          |                |                   |          |             |             |           |   €16 |       €9 |   €25 |
|                      |             | [Ringer Keys][rk]      |         |       |       |                                        |          |                |                   |          |             |             |           |   $20 |       $5 |   $25 |
|                      |             | [RNDKBD][rn]           |         |       |       |                                        |          |                |                   |          |             |             |           |   $18 |       $6 |   $24 |
| **Bit-C PRO**        | No          | [nullbits][nb]         |Black, White| No |   4MB | 4 (bottom row)                         |   Top    |       No       | Uses user LEDs    |  3 — RGB |    Yes      | 0           |   ???     |   $20 |       $0 |   $20 |
| **Blok**             | No          | [Boardsource][bs]      |  Black  |  Yes  |  16MB | 0, see also note (1) below             |   Mid    |       No       | Purple            |   RGB    |    No       | 2 (side)    |   ???     |   $14 |       $5 |   $19 |
| **Elite-Pi**         | No          | [1upkeyboards][1u]     |  Blue   |  Yes  |   2MB | 5 (bottom row), 2 (pads)               |   Mid    |   Pads (back)  | No                |   No     |    No       | 2 (front)   |   ???     |   $17 |       $0 |   $17 |
|                      |             | [Keebio][io]           |         |       |       |                                        |          |                |                   |          |             |             |           |   $13 |       $5 |   $18 |
| **Frood RP2040**     | [Yes][Ofr]  | [42.Keebs][42]         | Various |  No   |   4MB | 5                                      |   Mid    | Pins (top row) | No                |  Orange  |    No       | 2 (front)   |   GPIO19  |   €11 |       €5 |   €16 |
| **KB2040 Kee Boar**  | No          | [Adafruit][af]         |  Black  |  Yes  |   8MB | 2 (Qwiic), see also note (2) below     |   Top    | Pins (top row) | Green             |   RGB    |    No       | 2 (front)   |   ???     |    $9 |       $4 |   $13 |
| **key micro RP**     | No          | [BOOTH][bo]            |  Black  |  No   |   4MB | 0                                      |   Mid    |   Pads (back)  | No                |   No     |    No       |2 (side/back)|   ???     | ¥2700 |        ? |     ? |
| **Laitris**          | No          | [splitkb][sk]          |  Black  |  Yes  |  16MB | 5 (bottom row, 5V)                     |   Mid    |   Pads (back)  | Yes (back, GPIO24)|   RGB    |    No       | 1 (back)    |   ???     |   €15 |      €18 |   €33 |
| **Pro Micro RP2040** | [Yes][Opm]  | [SparkFun][sf]         |   Red   |  Yes  |  16MB | 2 (Qwiic connector)                    |   Top    |   Pads (back)  | Red               |   RGB    |    No       | 2 (front)   |   No      |   $11 |      $11 |   $22 |
| **RP2040 Pro Micro** | No          | [Tenstar Robot][tr]³   |  Black  |  No   | 4/16MB| 5 (bottom row), 3 (inset)              |   Mid    |       No       | No                |   RGB    |    No       | 2 (front)   |   ???     |    $3 |       $2 |    $5 |
| **Sea-Picro EXT**    | [Yes][Osp]  | [beekeeb][bk]          |  Black  |  No   |  16MB | 5 (bottom row), 1 (inset, 5V)          |   Mid    | Pins (top row) | No                |   No     |    Yes      | 0           |   GPIO19  |   $10 |       $8 |   $18 |
|                      |             | [Custom KBD][ck]       |  Black  |  Yes  |       |                                        |          |                |                   |          |             |             |           |   $17 |      $15 |   $32 |
| **Sea-Picro RST**    | [Yes][Osp]  | None                   |  Black  |  No   |  16MB | 0                                      |   Mid    | Pins (top row) | No                |   RGB    |    Yes      | 1 (front)   |   GPIO19  |       |          |       |
| **svlinky**          | [Yes][Osv]  | [fingerpunch][fp]      |  Black  |  No   |   8MB | 9 (VIK connector)                      |   Mid    |       No       | No                |   Yes    |    No       | 0           |   GPIO19  |   $15 |      $10 |   $25 |

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

 * Cast. — indicates whether the PCB is castellated or not.
 * Extra GPIO — indicates the number and location of any I/O pins beyond the [usual 18 for a
   ProMicro](https://cdn.sparkfun.com/assets/9/c/3/c/4/523a1765757b7f5c6e8b4567.png).
 * USB Port — all boards are USB C unless noted, a mid-mount board will typically result in an
   overall MCU thickness of 3.2mm (the thickness of a USB C port), while a top-mount board will be
   3.2mm plus the thickness of the PCB (typically 1.6mm).
 * USB Brk. Out — indicates whether there is access to the USB data (i.e. can a USB breakout board
   be used with this MCU), and the type and approximate location of the access points.
 * User LED — indicates whether there is an onboard LED (single colour or RGB) that can be accessed
   from firmware.
 * 1-Btn. Boot — indicates whether the board has a combined reset and boot circuit (e.g., a short
   press will reset, while a long press will reboot). This means that only one on-board reset/boot
   button is required and off-MCU reset buttons can be used to go into boot-loader mode (once
   installed and appropriately configured, QMK can also trigger this via [a double-tap of the reset
   button](https://docs.qmk.fm/#/platformdev_rp2040?id=double-tap)).
 * Buttons — indicates whether there are onboard reset/boot buttons and their general location
   (front of the board, back of the board, or facing sideways from the rear of the board).
 * VBus Det. — (do all RP2040s have this???)
 * Price — price of a single MCU before tax as of March 2024 in US dollars, euros or yen. To be used
   as a very rough guide to comparative cost.
 * Shipping — lowest available cost as of March 2024 in US dollars or euros of shipping one MCU to
   New York City (if possible).
 * Total — Price plus Shipping. Again, to be used as a very rough guide to comparative cost for a
   single MCU. Does not include cost savings for multiple units, etc.

### Notes on Rows

 1. Blok has [GPIO 16 and 17](https://peg.software/docs/blok) instead of 2 and 3 respectively.
 2. KB2040 has [GPIO 10, 18 and 19](https://learn.adafruit.com/adafruit-kb2040/pinouts) instead of
    21, 22 and 23 respectively.
 3. The unbranded “RP2040 Pro Micro” is available at [various AliExpress
    stores](https://www.aliexpress.com/w/wholesale-RP2040-Pro-Micro.html).
