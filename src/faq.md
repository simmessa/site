---
layout: page
title: Frequently Asked Questions
permalink: /faq/
nav_order: 100
---


# FAQs

- **If I flash this firmware, will I be able to revert to the original Anne Pro
firmware later?**

Yes. We use the original Anne Pro 2's bootloader to load our firmware, so
reverting is as easy as putting the keyboard into IAP mode and do an firmware
update with ObinsKit. (Note: We have noticed ObinsKit might have trouble restoring
when under macOS, but have had great success with Windows.)

- **I am having trouble building the firmware, what am I missing?**

First, please make sure you have fully read the install guide, this will help 
everyone in the discord server and yourself to save time. Since we are all 
volunteering to help eachother out. Also make sure you have all the required tool
chains installed. (gcc-arm-none-eabi, make, etc)

- **Flashing stuck on `device is Some("USB-HID IAP")`**

This one is interesting. I personally have encountered this a few times, but 
I have always been able to solve this by a) changing a usb port. b) restart computer.

- **Any advice for Windows users?**

Yes. In fact, I recommend windows users to build the firmware under WSL and flash the firmware
in native windows environment. (aka install rustc in windows and build annepro2-tools there).

This seems to work the best for most people. YMMV.
