# stainless/tkl

A handwired ISO tenkeyless keyboard (88 keys) on a stainless steel plate, driven by a Raspberry Pi Pico.

The switches are wired as a 12×9 matrix: each physical row is split into a left and a right half, and each column wire is shared between the two halves.

* Keyboard Maintainer: [Ciarán Coffey](https://github.com/ciarancoffey)
* Hardware Supported: Handwired, Raspberry Pi Pico (RP2040)
* Hardware Availability: Handwired; no PCB

Make example for this keyboard (after setting up your build environment):

    make stainless/tkl:default

Flashing example for this keyboard:

    make stainless/tkl:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down Escape (the key at (0,0) in the matrix) and plug in the keyboard
* **Physical reset button**: Hold the BOOTSEL button on the Pico while plugging it in
