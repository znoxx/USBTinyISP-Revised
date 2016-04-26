# USBTinyISP programmer revised

## General

This project is derived from http://www.simpleavr.com/avr/vusbtiny

It's a cheap and easy to make ISP programmer of AVR devices.

## Contents

* eagle - contains board and schematics in Eagle CAD layout
* firmware - program itself

## What's changed

* Issues in schematics corrected
* Aligned with newer V-USB stack
* Board layout optimized for "toner transfer" method and one layer
* SMD 0805 design

## How to build

To compile, you will need AVR-GCC stack. Just run **make** in firmware directory or flash pre-build vusbtiny.hex into the freshly build board.

### Fuse bit settings

* lfuse: 0xe1
* hfuse: 0x5d
* efuse: 0xff

## Further reading

Please refer to http://znoxx.me/2013/03/10/usbtinyisp_ili_opyat__programmator/ for description and some pictures. (In Russian, use "Translate"
 button in menu to translate to your language)
