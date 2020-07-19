---
layout: home
title: "Home"
nav_order: 0
---

# Open Anne Pro

This is an alternative firmware for the Anne Pro 2 Keyboard.

This is for the Anne Pro 2 keyboard, for the Anne Pro 1, please refer to the
[anne-key](https://github.com/ah-/anne-key) project.

# Why Custom Firmware

From my short and limited experience with the original firmware provided by ObinsLab,
I find it to be extremely buggy. One of the most significant problem being
compatibility in BIOS. Aside from buggy, I would also like to switch the "Magic FN"
from caps lock to other keys.

# Status

This project is still under heavy development and in its early stages. I would recommend
to always have a backup keyboard if you are going to participate in the project. (i.e. if
something arises you still have a second way to input keystrokes for long enough that you
can either restore to the Obins firmware or find a solution).

To see a list of To-Do items click [here]({% link contributing.md %})

## QMK
[QMK](https://qmk.fm/) is a powerful open source keyboard firmware used by
many open source keyboards that are on the market today. It is most famous
for its appearance in the Plank and ErgoDox EZ keyboards.

Currently, we have a fully functional port of the QMK firmware for both the c15
and c18 revision. (If you are unsure which one you have, read below.)
This includes key matrix function, which is the "most important" part of a keyboard,
I would say.

## AnnePro2-Shine
Shine is the custom firmware designed to run on the LED micro-controller of the
keyboard to control lighting effects. In Obins' words, this is the Light processor.

Currently this project is in its infancy, only very basic features has been tested.
It can act as a decent indicator light (e.g. Caps Lock) using the RGB LEDs. But
there is a lot of potential out there, as the firmware is only about 5KB in size
right now, and the microcontroller can hold 64/128 KB of code for the c15/c18
revision respectively.

## Bluetooth
Currently the bluetooth support is based on the original Obins BLE processor firmware,
which means you will not need to reflash the BLE chip if you have the latest stock 
firmware on it. Contact me in the discord if you need a copy of the stock BLE firmware
to flash.
