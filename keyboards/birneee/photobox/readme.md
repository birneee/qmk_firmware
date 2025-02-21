# PhotoBox Keys with Raspberry Pi 2040

Custom handwired one key keyboard. **See each individual board for pin information.**

* Hardware Availability: *n/a*

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb birneee/photobox/rp2040 -km via

Flashing example for this keyboard:

    qmk flash -kb birneee/photobox/rp2040 -km via

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Raspberry Pi 2040

To trigger Button 1, short together pins *GP4* and *GP5*.
To trigger Button 2, short together pins *GP6* and *GP7*.

Double-tap reset to enter bootloader mode. Copy the built uf2 file to the device by dragging the file to the new USB disk.

### Supported Hardware

* Raspberry Pi Pico
* SparkFun Pro Micro - RP2040
* Adafruit KB2040 - RP2040 Kee Boar
* ...and many more RP2040 based development boards